# Algorithms — An Analytical Note

An assignment submission for **Discrete Mathematics (MSc IT)** covering **Chapter 3 — Algorithms** from Kenneth H. Rosen's *Discrete Mathematics and Its Applications* (8th edition).

The project analyses classical algorithms both **analytically** (formal proofs, complexity analysis) and **empirically** (a Python implementation with an interactive dashboard).

| | |
|---|---|
| **Student** | Solanki Ruchit M. |
| **ID** | 202612085 |
| **Course** | MSc IT |
| **Subject** | Discrete Mathematics |
| **Instructor** | Prof. Gopinath Panda |
| **Reference** | K. H. Rosen, *Discrete Mathematics and Its Applications*, 8th ed., Ch. 3 |

## Contents

| File | Description |
|---|---|
| `Algorithms_Analytical_Note_202612085.pdf` | Compiled analytical note (the main report). |
| `Algorithms_Analytical_Note_202612085.tex` | LaTeX source of the analytical note. |
| `Algorithms_Implementation_202612085.ipynb` | Python notebook implementing and benchmarking the algorithms. |
| `algorithms_dashboard_202612085.html` | Self-contained interactive dashboard for exploring the results. |

## Topics Covered

- Formal definitions of algorithms and their properties.
- Pseudocode and algorithm design.
- Growth of functions: Big-O, Big-Omega and Big-Theta notation.
- Analysis of the complexity of representative algorithms.

## Viewing the Report

**PDF** — open `Algorithms_Analytical_Note_202612085.pdf` in any PDF reader.

**Dashboard** — open `algorithms_dashboard_202612085.html` in a web browser. It is a single self-contained file, so no server is required.

**Notebook** — open `Algorithms_Implementation_202612085.ipynb` in Jupyter Notebook, JupyterLab or VS Code.

## Building the Report from Source

The note is written in LaTeX and compiles with `pdflatex`:

```bash
pdflatex Algorithms_Analytical_Note_202612085.tex
```

## Running the Notebook

```bash
pip install jupyter
jupyter notebook Algorithms_Implementation_202612085.ipynb
```
