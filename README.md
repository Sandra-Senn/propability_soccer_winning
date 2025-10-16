# EURO 2023 Tournament Monte Carlo Simulation

A data science notebook project to simulate all rounds of the EURO 2023 football championship and predict tournament winners using Monte Carlo methods.


## Project Overview

This project leverages Monte Carlo simulation to model the progression and outcome of EURO 2023 football matches. By simulating each tournament round thousands of times, it generates probabilistic predictions for the overall winner. The calculation methods integrate custom metrics based on ELO and goal statistics. Notebook, supporting data, and results are included for full transparency and reproducibility.

## Folder Structure
```bash
root/
│
├── .idea/ # IDE/editor config files (ignore)
├── data/ # Data directory with supplemental files
│
├── OMC_WER.ipynb # Main Jupyter Notebook (simulation workflow)
├── README.md # This file
├── tournament_winners_ELO2.xlsx # Results: simulation winners based on ELO
```

## Requirements

- Python >= 3.8
- Jupyter Notebook

Recommended packages:
- numpy
- pandas
- openpyxl
- (optional: matplotlib or seaborn for plots)

Install dependencies (if a requirements file is provided):
```bash
pip install -r requirements.txt
```

Or individually:

```bash
pip install numpy pandas openpyxl
```


## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/yourusername/euro2023-montecarlo-sim.git
cd euro2023-montecarlo-sim
```
2. Open the main Jupyter notebook:
```bash
jupyter notebook OMC_WER.ipynb
```

3. Run all cells to perform the simulation and generate forecasts.
4. Review outputs in the notebook itself or consult final results (`tournament_winners_ELO2.xlsx`, `tournament_winners_GOALS2.xlsx`).

## Data Sources

- Simulation draws on internal and provided datasets (see `data/`)
- Results from each metric saved as Excel files
- All other data is generated within the notebook

## Usage

- The core workflow is contained in `OMC_WER.ipynb`
- Modify simulation parameters (number of runs, assumptions) directly in the notebook
- Extend or adapt calculations by editing relevant notebook cells

## Results

- Main results: Probabilities of each team winning the European Championship, saved in Excel spreadsheets
- Output files: `tournament_winners_ELO2.xlsx` and `tournament_winners_GOALS2.xlsx` (based on two simulation strategies)

## Contributing

Contributions, bug reports, and improvement suggestions are welcome via pull request or issue.

