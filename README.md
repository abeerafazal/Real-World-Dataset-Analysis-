# Real World Dataset Analysis

## Project title
Analyze a Real World Dataset and Present Findings

## Dataset
Palmer Penguins dataset. It contains 344 observations of three penguin species from the Palmer Archipelago in Antarctica, with body measurements and categorical details.

Original dataset page:
https://huggingface.co/datasets/SIH/palmer-penguins

Direct CSV:
https://huggingface.co/datasets/SIH/palmer-penguins/resolve/main/penguins.csv

Dataset license: CC0 1.0, as described on the dataset page.

## Files
- `real_world_penguins_analysis.ipynb`: complete Jupyter Notebook
- `requirements.txt`: Python libraries required
- `report.docx`: written project report

The notebook downloads the original dataset from the public source the first time it runs. An internet connection is required. It then saves a local copy named `penguins.csv`.

## Setup
1. Install Python 3.
2. Open a terminal in this project folder.
3. Run `python -m pip install -r requirements.txt`.
4. Run `jupyter notebook`.
5. Open `real_world_penguins_analysis.ipynb`.
6. Run all cells from top to bottom.

The notebook creates `penguins_cleaned.csv` after preprocessing. Charts are displayed during execution.

## Analysis included
Dataset overview, data types, missing value checks, duplicate checks, missing value imputation, species and island counts, group summaries, bar charts, scatter plot, histogram, correlation analysis, and IQR outlier review.

## Data citation
Horst AM, Hill AP, Gorman KB (2020). palmerpenguins: Palmer Archipelago (Antarctica) penguin data. R package version 0.1.0. DOI: https://doi.org/10.5281/zenodo.3960218
