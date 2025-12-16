# LaTex

*Basic template for writing LaTeX documents*

## About

This repository provides a simple and clean template for writing documents in LaTeX. It’s designed to help you get started quickly with a ready-to-use structure, including a main document, separate content files, batch scripts for building, and a set of supporting folders.

## Directory Structure

```plaintext
.vscode/             - VS Code workspace settings  
content/             - Folder for main document parts (.tex)  
pdfs/                - Folder for exported PDFs  
pictures/            - Any image resources used in your document  
00_main.tex          - Main LaTeX file  
00_main.pdf          - Compiled PDF output (for reference)  
01_Intro.tex         - Example of split content file  
run.bat              - Windows batch script to build the document  
run_short.bat        - Shorter/reduced build script  
.gitignore           - Typical ignore file  
```

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/mattiaAsto/LaTex.git
   ```

2. **Edit your document**

   * Modify `00_main.tex` as the main LaTeX entry-point.
   * Use the `content/` folder for chapters or sections (`01_Intro.tex`, etc).
   * Place figures in `pictures/` and reference them from your .tex files.

3. **Compile the document**

   * Windows: run `run.bat` (full build) or `run_short.bat` (lighter build).
   * Other OS: adapt batch scripts into shell scripts or use LaTeX build tools (e.g., `pdflatex`, `xelatex`, `latexmk`).

4. **View output**

   * PDF output will appear in `pdfs/` or as `00_main.pdf`.
   * Review and iterate until the document is complete.

## Features

* Modular structure for managing long documents.
* Batch scripts for easy compilation.
* Clean template to start projects quickly.
* Organized folders for resources and output.

## Customisation

* Rename `00_main.tex` and adjust scripts if needed.
* Change LaTeX engine (`xelatex`, `lualatex`) in scripts if preferred.
* Add folders for bibliography (`bib/`), appendices (`appendix/`), or macros (`style/`).
* Add packages/configuration in the main .tex preamble.

## License

This template is provided **as-is**. Use, modify, and distribute freely. Add a license file (MIT/GPL) if desired.

## Contributing

Suggestions, improvements, or bug fixes are welcome via issues or pull requests.

---

Happy LaTeX writing! 📝
