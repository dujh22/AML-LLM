# **Advanced Machine Learning: Large Language Models**

Welcome to the GitHub repository for the book "Advanced Machine Learning: Large Language Models"! This project serves as a platform for storing and maintaining source code, data, errata, and update information related to the book.

---

## **📖 Book Introduction**

This book systematically introduces the theoretical foundations, cutting-edge technologies, practical applications, and future trends of Large Language Models (LLMs), dedicated to providing detailed and practical content for researchers, engineers, and learners.

**Author Information:**

- **Jie Tang** - Tsinghua University
- **Jinhua Du** - Tsinghua University
- Other collaborators

---

## **🚀 Version Updates**

| **Version** | **Date** | **Major Updates**                           |
| ----------------- | -------------- | ------------------------------------------------- |
| v1.0              | 2024-01-26     | First draft Word version officially released      |
| v2.0              | 2025-08-01     | Second draft LaTeX version preparation: Chapter 1 |
| v2.1              | 2025-08-       |                                                   |

---

## **🛠️ Repository Structure**

```
AML-LLM/
├── word/                    # Original Word format documents
│   └── word_250125/        # Word documents from January 25, 2025
│       ├── 1. Course Introduction.docx
│       ├── 2. Deep Learning Fundamentals.docx
│       ├── 3. Transformer Fundamentals.docx
│       ├── 4. In-Context Learning and Model Pre-training.docx
│       ├── 5. Post-training: Supervised Fine-tuning.docx
│       ├── 6. Post-training: Reinforcement Learning from Human Feedback.docx
│       ├── 7. Scientific Evaluation and Alignment of Large Language Models.docx
│       ├── 8. Agents.docx
│       ├── 9. Safety and Evaluation of Large Models.docx
│       ├── 10. AML Mid-term Report.docx
│       ├── 11. Multimodal Language Models.docx
│       ├── 12. Specialized Model Collaboration and Speech Models, Data and TTC.docx
│       ├── 13. Generative Models.docx
│       ├── 14. Week 15.docx
│       ├── 15. Week 16.docx
│       ├── Latest Research and Technical Discussion on Large Models.docx
│       ├── Advanced Machine Learning Course References.docx
│       ├── Advanced Machine Learning Course Glossary.docx
│       └── Cover.pdf
├── latex/                   # LaTeX typesetting files
│   ├── latex/              # Main LaTeX files
│   │   ├── book.tex        # Main document
│   │   ├── title.tex       # Title page
│   │   ├── preface.tex     # Preface
│   │   ├── chapter1.tex    # Chapter 1
│   │   ├── chapter2.tex    # Chapter 2
│   │   ├── figures/        # Image resources
│   │   ├── attachment/     # Attachments
│   │   ├── book.pdf        # Generated PDF
│   │   └── readme.md       # LaTeX usage instructions
│   └── latex_raw/          # Original LaTeX files
├── README.md               # English documentation
├── README_ZH.md            # Chinese documentation
└── .gitignore              # Git ignore file
```

---

## **🔧 How to Use**

### Clone this repository:

```bash
git clone https://github.com/yourusername/AML-LLM.git
cd AML-LLM
```

### View documents:

- **Word format**: View Word documents for each chapter in the `word/word_250125/` directory
- **PDF format**: View the generated `book.pdf` in the `latex/latex/` directory
- **LaTeX source code**: View typesetting source code in the `latex/latex/` directory

### Compile LaTeX documents:

```bash
# First ensure your environment includes packages that can compile LaTeX.
# Install dependency packages to your environment: e.g., pip install Pygments

cd latex/latex
xelatex -shell-escape book.tex
xelatex -shell-escape book.tex
```

It is recommended to read alongside the physical book or electronic version for the best learning experience.

---

## **📚 Chapter Content Overview**

This book includes the following main chapters:

1. **Course Introduction** - Overview of Large Language Models
2. **Deep Learning Fundamentals** - Neural Network Basic Theory
3. **Transformer Fundamentals** - Detailed Explanation of Transformer Architecture
4. **In-Context Learning and Model Pre-training** - Pre-training Techniques
5. **Post-training: Supervised Fine-tuning** - SFT Techniques
6. **Post-training: Reinforcement Learning from Human Feedback** - RLHF Techniques
7. **Scientific Evaluation and Alignment of Large Language Models** - Model Evaluation and Alignment
8. **Agents** - Agent Technologies
9. **Safety and Evaluation of Large Models** - Safety and Evaluation
10. **Multimodal Language Models** - Multimodal Technologies
11. **Specialized Model Collaboration and Speech Models** - Specialized Models and Speech
12. **Generative Models** - Generative Models
13. **Latest Research Progress** - Cutting-edge Technology Discussion

---

## **🙌 Contribution Guidelines**

We welcome readers and community contributors to actively submit feedback, propose errata, or contribute code.

* Submit Issues for feedback on book content
* Submit Pull Requests for fixing errata or supplementing content
* Submit Pull Requests for improving LaTeX typesetting or adding new features

---

## **📜 Open Source License**

This project is licensed under the [MIT License](LICENSE).

---

## **📧 Contact Authors**

* **Jie Tang** - Tsinghua University
* **Jinhua Du** - Tsinghua University dujh22@mails.tsinghua.edu.cn

---

## **🔗 Related Links**

* [Tsinghua University Homepage](https://www.tsinghua.edu.cn/)
* [GitHub Project Page](https://github.com/dujh22/AML-LLM)

---

*Last updated: August 9, 2025*
