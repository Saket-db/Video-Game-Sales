# Video Game Sales Analysis

This repository contains a Google Colab / Jupyter notebook and dataset used to explore video game sales. The analyses include data cleaning, basic statistics and visualizations (barplots, boxplots, line charts) for National and Global sales and profits across regions, publishers and years.

## Contents

- `VideoGameSales.ipynb` — Notebook with data loading, cleaning, EDA and visualizations (Colab-ready).
- `VideoGamesSales.csv` — Raw dataset used by the notebook.

## Quick summary

The notebook performs:
- Reading the CSV into a pandas DataFrame
- Removing duplicate rows
- Handling null values (Region, Publisher, etc.)
- Cleaning numeric columns (removing `$` and commas and converting to float)
- Renaming columns for clarity
- Visualizing results with Matplotlib and Seaborn (bar plots, box plots, line charts)

## Libraries / Dependencies

The notebook uses the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn

The notebook also uses Colab-specific functionality:
- google.colab (for mounting Google Drive)

If you run the notebook locally, you only need the first four packages. If you run in Google Colab, the Colab runtime already provides these packages and the `google.colab` module.

## Install dependencies (local)

Install the packages via pip (PowerShell / terminal):

```bash
pip install pandas numpy matplotlib seaborn
# optional: install jupyter if you want to run the notebook locally
pip install jupyter
