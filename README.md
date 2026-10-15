# IDP Report — Fluoride Adsorption Optimization Using GTMAC-Modified Coconut Fiber and Machine Learning

LaTeX source for the Interdisciplinary Project (IDP) report at RV College of Engineering.

Fluoride contamination in drinking water is a serious health concern. This project studies low-cost, eco-friendly removal using GTMAC-modified coconut fiber as an adsorbent, and models adsorption with a hybrid approach: a Langmuir isotherm baseline corrected by a machine-learning residual model.

**Code and data:** [Amritesh-co/langmuir-ml-residual-correction](https://github.com/Amritesh-co/langmuir-ml-residual-correction)

## Report structure

| Chapter | Content |
| --- | --- |
| 1 | Introduction and motivation |
| 2 | Fundamentals of adsorption and isotherm models |
| 3 | System design |
| 4 | Implementation |
| 5 | Modelling — Langmuir baseline and hybrid ML diagnostics |
| 6 | Results and discussion |
| 7 | Conclusion and future work |
| Appendix | Supplementary material |

## Building the PDF

The sources are under `source/`. Compile with any LaTeX distribution (TeX Live / MiKTeX) or upload the folder to Overleaf:

```bash
cd source
latexmk -pdf main.tex
```

A compiled copy is included at [`source/main.pdf`](source/main.pdf).

Bibliography: `source/AuxFiles/ProjectBib.bib` · Packages: `source/AuxFiles/Packages.tex`
