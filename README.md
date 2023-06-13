# LaTeX VSCode IEEE Conference Paper Format Template

Modified from [original LaTeX template from IEEE](https://www.ieee.org/conferences/publishing/templates.html).

This template is an altered LaTeX template sourced from IEEE, featuring enhanced division of topics among chapters and references. It effectively streamlines and declutters the document, ensuring a more polished and organized workflow.

## Requirements

Refer the requirements from [latex-workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop).

### For Windows

You can use either [MiKTeX](https://miktex.org/) or [TeX Live](https://www.tug.org/texlive/). Install as instructed.

### For macOS

Install [MacTeX](https://www.tug.org/mactex/) as instructed from the website.

### For Linux

Install the required package for `pdflatex` and `bibtex` according to your chosen distro.

For Ubuntu:

```bash
sudo apt-get -qq update && sudo apt-get install -y --no-install-recommends \
    dvipng texlive-latex-recommended \
    texlive-fonts-recommended \
    texlive-latex-extra \
    texlive-fonts-extra \
    texlive-bibtex-extra biber xzdec
```

For Manjaro:

```bash
pacman -Syu texlive-core texlive-fontsextra texlive-latexextra texlive-science texlive-bibtexextra biber
```

## Usage

- Make modifications to the `.tex` files and `references.bib` file according to your requirements. If you need to include additional chapters, create a new `.tex` file in the "chapters/" directory and add the chapter reference in the `document.tex` file.
- If you need to define custom rules or include new packages, you can edit the `ieee-paper.sty` file.
- To include images or any other resources, place them in the "resource/" folder.
- Before publishing your document, ensure that you remove any template texts or placeholders from the content.

### Useful Shortcuts from Latex Workshop

| Shortcut             | Location | Usage                                          |
| -------------------- | -------- | ---------------------------------------------- |
| `ctrl` + `alt` + `v` | `.tex`   | open pdf in side window                        |
| `ctrl` + `lmb`       | `.pdf`   | open `tex` file according to cursor in `pdf`   |
| `ctrl` + `alt` + `j` | `.tex`   | scroll `pdf` according to cursor in `tex` file |

## Contributions

Feel free to open issues and contribute to this repository! You can report any problems or feature requests by issuing new [issues](https://github.com/alvinwilta/ieee-conference-latex/issues) and contributing by forking this repository and opening up new [pull requests](https://github.com/alvinwilta/ieee-conference-latex/pulls).

Template created by [Alvin Wilta](https://github.com/alvinwilta), 2023.
