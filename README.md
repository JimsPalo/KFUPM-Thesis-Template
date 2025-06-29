
# KFUPM Thesis Template

This repository provides a structured LaTeX template for Master’s and Ph.D. theses at **King Fahd University of Petroleum & Minerals (KFUPM)**. It is designed to comply with the formatting requirements of the Deanship of Graduate Studies (DGS), incorporating Arabic and English support, glossaries, customised title pages, and reference formatting.

---

## 📦 Contents

The ZIP file includes:

- `main.tex` – Main file for compiling the thesis
- `kfupm_thesis.cls` – Official KFUPM thesis class file
- `chapters/` – Example chapters structured modularly
- `images/` – Folder for figures and diagrams
- `bibliography.bib` – BibTeX file for references
- `glossaries/` – Definitions for symbols and abbreviations
- `appendices/` – Appendix examples
- `Makefile` – Optional build automation (for UNIX systems)
- `README.md` – Repository documentation

---

## 🚀 Getting Started

### 1. Requirements

- **XeLaTeX** compiler (for Arabic + English)
- Recommended editors: Overleaf, TeXstudio, VSCode with LaTeX Workshop

### 2. Compilation

To compile the template:

```bash
xelatex main.tex
biber main
xelatex main.tex
xelatex main.tex
````

Or use a LaTeX editor with a predefined build profile.

---

## ✍️ Customisation

* Modify the fields in `main.tex`:

  * `\title{Your Thesis Title}`
  * `\author{Your Name}`
  * `\dept{Your Department}`
  * Arabic entries using `\artitle`, `\arname`, `\ardept`, `\ardate`

* Define your abbreviations and symbols in `glossaries/`

* Use `\input{chapters/chapter_name}` to structure content

---

## 📚 Features

* Dual-language support (English + Arabic)
* Glossaries for:

  * **Abbreviations**
  * **Symbols**
* Bibliography handled via BibTeX
* Compliant formatting for:

  * Title and committee pages
  * Abstracts (Arabic and English)
  * List of figures, tables, and symbols

---

## 🏷 License

This template is provided under the [MIT License](LICENSE), as modified from KFUPM’s publicly available thesis class.

---

## 📬 Contributions

Pull requests and suggestions to improve usability or documentation are welcome!

---

## 📞 Contact

If you encounter issues or have improvement suggestions, feel free to open an issue or contact:

**Author:** \[Your Name]
**Email:** \[Your University Email]

---

> Developed for graduate students at KFUPM pursuing MSc and PhD degrees. Maintained to ensure compliance and ease of use.

```
