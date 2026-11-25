# Submisi-KBJ-2026
This repository is a place for uploading research results in the form of paper draft, source code, dataset(s), and other supporting aspect as a form of accountability for Informatics Department Master's student in Network Centric Computation lecture class of Institut Teknologi Sepuluh Nopember (ITS).

**!!Any form of accountability regarding the originality of the research is on the author!!**

## Struktur Direktori
```text
/
└── Student's_Full_Name
    ├── README.md
    ├── LICENSE
    ├── paper
    │   ├── article.tex
    │   ├── article.bib
    │   ├── article.docx
    │   ├── article.pdf
    │   └── image.png
    ├── src
    ├── results
    └── datasets.md
```

### Directory Explanation
1. Each student clone this repo then add a folder with each student full name.
1. README.md contains full name, NIM, title, abstract, and keywords, and license scope.
1. "LICENSE" contains the license of the source code and the paper. LICENSE should be fall under either on the [Open Source Software](https://opensource.org/osd), [Free Software](https://www.gnu.org/philosophy/free-sw.html), or [Creative Common](https://creativecommons.org/cc-license-guidance/) specification.
1. "paper" directory contains raw paper file (tex, bib, png, docx) as well as pdf file of the paper.
1. "src" contains source code of the research.
1. "results" contains the research result(s), can be in the form of table and/or picture complete with brief explanation of the research result(s).
1. "datasets.md" contains url(s) from each dataset(s) that is used in the research.

> It is recommended to use some kind of dependency management system (Docker, nix-flake, or devenv) for easier research replication and reproducibility.

> If the above are not included, it is required for the student to give details in the form of library, framework, and programming language version that is used at the end of the "README.md" file.

### Submission Method
Clone -> Add -> Commit -> Pull Request

