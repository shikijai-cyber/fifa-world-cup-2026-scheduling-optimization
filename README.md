# FIFA World Cup 2026 Scheduling Optimisation

## Overview
This project builds optimisation models for the FIFA World Cup 2026 draw and scheduling problem. It uses Python and Pyomo to support group formation, group-letter assignment, and stadium assignment decisions under practical tournament constraints.

## Features
- Loads team, pot, confederation, ranking, spectator, stadium, and allocation data from Excel
- Formulates mathematical optimisation models with Pyomo
- Applies tournament-style constraints for fair group formation
- Compares optimised allocations against actual or reference allocations
- Produces plots for stadium capacity and popularity comparisons

## Project structure
```text
notebooks/     Optimisation notebook
data/          Input workbook used by the notebook
docs/          Portfolio summary and supporting notes
requirements.txt
```

## Installation
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

You will also need a Pyomo-compatible solver installed locally, such as CBC, GLPK, HiGHS, or another MILP solver.

## Usage
Open and run:
```bash
jupyter notebook notebooks/world_cup_optimization.ipynb
```

The notebook expects:
```text
data/world_cup_2026_input.xlsx
```

## Technologies used
Python, Pyomo, pandas, NumPy, Matplotlib, Excel.

## Suggested portfolio improvement
Add a short visual screenshot of the final allocation and a one-paragraph explanation of the optimisation objective to make the repository easier for recruiters to scan.
