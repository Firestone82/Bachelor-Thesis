# Bachelor-Thesis

> **VŠB-TUO** — Bachelor's thesis · 2024

![LaTeX](https://img.shields.io/badge/LaTeX-TeX-blue)

LaTeX source for the Bachelor's thesis *Trails Through Shadows* (2024), submitted at VŠB-TUO, Faculty of Electrical Engineering and Computer Science.

## About

The project was a collaborative hybrid physical-digital narrative game — merging tabletop mechanics with digital interfaces for dungeon exploration and branching storylines. My primary contribution was the **Dashboard** (Frontend), built with Python and Django, covering the backend API, database schema, and image generation pipeline.

**Team:** Pavel Mikula, [Barbora Kovalská](https://github.com/Kkobarii), [Martin Korotwitschka](https://github.com/rcMarty), [Miroslav Osoba](https://github.com/Orfian)

The full game source lives in the [Trails-Through-Shadows](https://github.com/Trails-Through-Shadows) GitHub organization:
- [Backend API](https://github.com/Trails-Through-Shadows/TTS-API)
- [Dashboard (my work)](https://github.com/Trails-Through-Shadows/TTS-Dashboard)
- [Game Frontend](https://github.com/Trails-Through-Shadows/TTS-Frontend)

Published thesis: [DSpace VŠB-TUO](https://dspace.vsb.cz/handle/10084/153760)

## Screenshots

### Dashboard

<p align="center">
  <img src="https://github.com/Trails-Through-Shadows/TTS-Dashboard/blob/master/static/img/assets/dashboardTable.png" alt="Class Table" width="48%">
  &nbsp;
  <img src="https://github.com/Trails-Through-Shadows/TTS-Dashboard/blob/master/static/img/assets/dashboardWorkbenchPart.png" alt="Part Workbench" width="48%">
</p>

<p align="center">
  <img src="https://github.com/Trails-Through-Shadows/TTS-Dashboard/blob/master/static/img/assets/dashboardWorkbenchCampaign.png" alt="Campaign Workbench" width="48%">
  &nbsp;
  <img src="assets/board-view.png" alt="Final board game design" width="48%">
</p>

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
