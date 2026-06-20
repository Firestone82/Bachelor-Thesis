# Bachelor-Thesis

> **VŠB-TUO** — Bachelor's thesis · 2024

![LaTeX](https://img.shields.io/badge/LaTeX-TeX-blue)

## About

LaTeX source for the Bachelor's thesis *Trails Through Shadows* (2024), submitted at VŠB-TUO, Faculty of Electrical Engineering and Computer Science.

The project was a collaborative hybrid physical-digital narrative game — merging tabletop mechanics with digital interfaces for dungeon exploration and branching storylines. My primary contribution was the **Dashboard**, built with Python and Django, covering the backend API, database schema, and image generation pipeline.

The full game source lives in the [Trails-Through-Shadows](https://github.com/Trails-Through-Shadows) GitHub organization.

Published thesis: [DSpace VŠB-TUO](https://dspace.vsb.cz/handle/10084/153760)

## Build

Requires a full TeX Live or MiKTeX installation.

1. Compile the document:
   ```bash
   pdflatex main.tex
   biber main
   pdflatex main.tex
   pdflatex main.tex
   ```

   Or open `main.tex` in [Overleaf](https://overleaf.com) or TeXstudio.

## License

© Pavel Mikula, 2024. All rights reserved.
