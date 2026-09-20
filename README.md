# Mapping the Creative Economy: A Topological Analysis of Creative Specialisation and Socioeconomic Context in England and Wales (2011-2014)

Code and supporting materials for an MSc research project examining
the structure of creative economies across TTWAs in
England and Wales.

## Repository structure

- `notebooks/` - data preparation, analysis and robustness checks
- `data/` - source-data instructions and derived analytical datasets
- `outputs/` - figures and tables produced by the analysis

## Analysis workflow

1. `01_nesta_data_prep.ipynb`
2. `02_census_data_prep.ipynb`
3. `03_t_tests.ipynb`
4. `04_ball_mapper.ipynb`
5. `05_ball_mapper_analysis.ipynb`
6. `06_robustness.ipynb`

## Data

The analysis uses Nesta creative industries data (Creative Nation) and 2011 Census data. Raw source data are not included in this repository. Instructions
for obtaining them are provided in `data/README.md`.

## Software

Python version: 3.13.6

Required packages are listed in `requirements.txt`.

## Reproduction

Run the notebooks in numerical order.
