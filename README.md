# Self-assembly of Berberine-based Herbal Small Molecules

## Overview
This repository presents a reproducible workflow for studying the self-assembly and antibacterial mechanisms of herbal small molecules (e.g. berberine) using molecular dynamics simulations and data analysis.
The project is part of my MSc research at Nanjing Agricultural University, focusing on self-assembly behavior relevant to antimicrobial applications in aquaculture.

## Methods
- Molecular Dynamics simulations using **GROMACS**
- Force field: (e.g. GAFF / OPLS/AA — specify if known)
- Trajectory analysis and visualization using **Python** (MDAnalysis, NumPy, Matplotlib)

## Repository Structure
- `notebooks/analysis.ipynb`: end-to-end analysis pipeline (load trajectory → analyze → plot)
- `scripts/`: example scripts for running MD simulations
- `results/figures/`: key figures generated from simulations
## Key Results (Preliminary)
Below is an example result illustrating aggregation behavior of berberine molecules during MD simulation:
![example_figure](results/figures/example.png)

## Reproducibility
The analysis can be reproduced by running the notebook:
```bash
conda env create -f environment.yml
conda activate selfassembly
jupyter notebook notebooks/analysis.ipynb
