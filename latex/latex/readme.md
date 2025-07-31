# LaTeX 中文书籍模板

> 本模板用于使用LaTeX排版中文书籍。

# Quick Start

首先下载并安装[texlive 2021](https://www.tug.org/texlive/)。

安装[minted](https://ctan.org/pkg/minted?lang=en)包。

pip install Pygments

然后执行如下命令。

```shell
git clone git@github.com:NelsonCheung-cn/latex-book-template.git
cd latex-book-template
xelatex -shell-escape book.tex
xelatex -shell-escape book.tex

如果存在各个章节的参考文献，则变化为
xelatex -shell-escape book.tex
bibtex chapter1.aux
// 将生成的chapter_1.bbl文件手动重命名为chapter_1.tex.bbl
xelatex -shell-escape book.tex
```

生成的[book.pdf](book.pdf)为模板示例。

或者直接将项目上传至overleaf，然后将compiler更换成XeLaTeX即可编译。

部分效果如下(github的内嵌pdf显示器可能无法显示中文......)。

# Introduction

本模板使用 `ctexbook`作为 `documentclass`，见 `book.tex`，如下所示。

```latex
\documentclass[openany,10pt,UTF-8,CJK,GBK]{ctexbook}

\usepackage[a4paper,twoside,width=15cm]{geometry}

\include{package.tex}

\begin{document}

\frontmatter

\include{title.tex}

\vspace*{\fill}
    \begin{center}
        \textit{谨以此书献给我的家人。}
    \end{center}
\vspace*{\fill}

\include{preface.tex}

\tableofcontents

\mainmatter

\include{chapter_1.tex}
\include{chapter_2.tex}
\include{chapter_3.tex}
\include{chapter_4.tex}
\include{chapter_5.tex}
\include{chapter_6.tex}

\include{attachment.tex}

\end{document}
```

由于书籍模板常用于排版大量文字，模板的每一个部分通过 `\include`命令包含进来，`\inculde`命令包含的 `tex`文件如下所示。

+ `package.tex`：模板用到的包。
+ `title.tex`：标题。
+ `preface.tex`：前言。
+ `chapter_X.tex`：第X章的内容。
+ `attachment.tex`：附录。


# 工具

您可以通过将Word文档另存为网页格式来快速导出所有图片。导出步骤：

1. **打开Word文档** ：首先，打开您想要导出图片的Word文档。
2. [ **另存为网页格式** **：点击菜单栏中的“文件”，然后选择“另存为”。在弹出的对话框中，选择保存路径，并在“保存类型”下拉菜单中选择“网页（** *.htm;* **.html）”选项。点击“保存”按钮。** ](https://jingyan.baidu.com/article/63acb44aaa49fa21fcc17eab.html)
3. [ **确认保存** **：如果弹出警告框，选择“继续”以确认保存操作。此时，Word会生成一个网页文件和一个与之同名的文件夹。** ](https://jingyan.baidu.com/article/3f16e003fc537c2590c1036b.html)
4. [ **查找导出的图片** **：打开刚才保存的文件夹，您会看到一个名为“XXX.files”的文件夹（其中XXX为您的Word文档名）。双击进入该文件夹，您将看到文档中所有的图片。** ](https://zhuanlan.zhihu.com/p/112342316)
