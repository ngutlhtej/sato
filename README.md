# sato
# Monolingual dictionary project related to constructed auxiliary languages ISO 639-2 "tlh".

LaTeX-based documentation project.

## Contributors
Unless it makes sense, try to limit each commit to one entry update and specify it in the log.
Format (png picture optional):
```
\entry{baghneQ}{dip}{tera' SommI'. SopmeH ghevjurHom.}[bagneq.png]
\entry{baH}{wot}{HIvmeH pagh HubmeH peng puvmoH.}
```

## Output

The generated PDF is available here:

👉 [https://ngutlhtej.github.io/sato/](https://ngutlhtej.github.io/sato/)

## Source License

Source files
Licensed under the [GNU General Public License v3.0 or later (GPLv3+)](LICENSE)

## Output License

Generated PDF (`sato.pdf`):  
Licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)](LICENSE-PDF.txt)

## Build

This repository uses GitHub Actions to compile `sato.tex` to PDF using `xelatex` and deploy the result via GitHub Pages.
