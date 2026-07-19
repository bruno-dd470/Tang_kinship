# Tang Kinship under the Test of the 64→20 Invariant

**Algebraic Topology, Alliance Filtration, and Social Homeostasis**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21442293.svg)](https://doi.org/10.5281/zenodo.21442293)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![MD](https://img.shields.io/badge/MD-blue?logo=markdown)](./Tang_kinship_en.md)
[![PDF](https://img.shields.io/badge/PDF-red?logo=adobeacrobatreader)](./Tang_kinship_en.pdf)

## Overview

This repository contains the research article **"Tang Kinship under the Test of the 64→20 Invariant"** by Bruno DE DOMINICIS.

The article demonstrates that the marriage rules and alliance structure of the Tang dynasty (618–907 CE) are not mere cultural constructs, but obey the **same universal topological constraint** as:

- 🧬 **The genetic code** (64 codons → 20 amino acids)
- 🗣️ **Chinese phonology** (24 initials → 20 functional classes)
- ⚛️ **Nuclear and atomic physics** (Λ72 lattice / Clifford algebra)

Using **Clifford algebra Cl(6,0)** and the geometry of the **Merkabah** (level-3 double tetrahedron), we show how the 64 possible matrimonial configurations are topologically filtered into **20 stable equivalence classes** (the alliance attractors). This filtration acts as a social "Pauli exclusion principle" — preventing frustrated configurations (incest, *Tongxing*) and ensuring the **negentropic homeostasis** of the Chinese imperial system.

The article also contrasts this structural stability with the **Western schism** (the "Catastrophe of Ravenna"), which broke topological homeostasis by extending the incest taboo to the 14th canonical degree.

---

## Key Theoretical Framework

| Concept | Description |
|---------|-------------|
| **Cl(6,0)** | Clifford algebra generating the 64 relational configurations (lineage, generation, age, sex, consanguinity, affinity). |
| **Merkabah Filtration** | Level-3 double tetrahedron geometry reducing the 64 states to 20 attractors via the geometric neighbourhood rule. |
| **12 Pentads** | Fundamental regulatory units; partitioned into two tropical belts ($C_P$, $C_N$) and two polar thresholds ($P_4$, $N_4$). |
| **Sheng / Ke Modes** | Generative vs. Regulatory dynamics along the belts, correlating with historical phases (apogee, crisis, decline). |
| **Λ72 Lattice** | Exceptional 72-dimensional lattice providing the spectral realization of the invariant (15 universal constants $\beta_k$). |
| **Social Negentropy** | The system's ability to "digest time" by transforming historical events into durable relational structures. |

---

## Repository Structure

```
.
├── README.md                     # This file
├── .gitignore                    # Excludes trash/, LaTeX build files, IDE configs
├── LICENSE                       # License file (CC BY-NC 4.0)
│
├── Tang_kinship_en.md            # Main article source (Markdown + YAML metadata)
├── Tang_kinship_en.pdf           # Compiled PDF (ready to read)
├── template_tang.tex             # LaTeX template for PDF generation
├── ieee.csl                      # IEEE citation style
├── Tang-kinship-en.bib           # English bibliography (Zotero/BibTeX)
├── Tang-kinship-fr.bib           # French bibliography (auxiliary)
│
└── References/                   # External source materials (PDFs)
    ├── NEBE 72 dimensional lattice 1008.2862v3.pdf
    ├── Zero to Infinity_ The Foundations of Physics (Rowlands).pdf
    ├── Viguier/
    │   ├── Ravenne_Leçon_de_droit_n°6_2021.pdf
    │   └── Ravenne_Leçon_de_droit_n°6_2021_eng.pdf
    └── UMMO/
        ├── D105-1.pdf
        ├── D105-2.pdf
        ├── D541.pdf
        ├── D59-1.pdf
        └── NR-20.pdf
```

> **Note**: The `trash/` folder (containing drafts and AI exchanges) is ignored by Git via `.gitignore`.

---

## How to Compile the PDF

### Dependencies
- [Pandoc](https://pandoc.org/) (>= 2.0)
- A LaTeX distribution with `xelatex` (e.g., TeX Live or MiKTeX)
- Required LaTeX packages: `microtype`, `rotating`, `textcomp`, `upquote`, `titlesec`, `geometry`

### Compilation command
From the repository root, run:

```bash
pandoc Tang_kinship_en.md --template=template_tang.tex --bibliography=tang-kinship-en.bib --biblatex --toc --toc-depth=2 -o Tang_kinship_en.tex
latexmk -xelatex Tang_kinship_en.tex
```
This will generate the final PDF with the table of contents, proper margins, and IEEE citation formatting.

---

## How to Cite

If you use this work in your research, please cite it using the following BibTeX entry:

```bibtex
@article{dedominicis_tang_2026,
  title = {Tang Kinship under the Test of the 64→20 Invariant: Algebraic Topology, Alliance Filtration, and Social Homeostasis},
  author = {De Dominicis, Bruno},
  year = {2026},
  doi = {10.5281/zenodo.xxxxxxx},
  url = {https://github.com/bruno-dd470/Tang_Kinship}
}
```

---

## License

This work is licensed under a **Creative Commons Attribution-NonCommercial 4.0 International License** (CC BY-NC 4.0).  
You are free to share and adapt the material for non-commercial purposes, provided you give appropriate credit.

---

## Author

**Bruno DE DOMINICIS**  
ORCID: [0009-0009-0380-3056](https://orcid.org/0009-0009-0380-3056)

For questions or collaboration, please open an issue in this repository or contact the author directly.

---

## Acknowledgments

The author thanks the contributors to the TBDB database (Nicolas Tackett), the foundational work of Damien Viguier on the Ravenna controversy, and the mathematical insights of Peter Rowlands and Gabriele Nebe. Special thanks to the open-source community for maintaining Pandoc, LaTeX, and Zotero.

