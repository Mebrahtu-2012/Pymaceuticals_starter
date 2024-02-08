# Pymaceuticals Anti-Cancer Medication Study Analysis

## Overview
This repository contains the analysis of a pharmaceutical company's study on potential treatments for squamous cell carcinoma (SCC), a form of skin cancer. The analysis includes data preparation, summary statistics, visualization of data, identification of outliers, and correlation analysis.

## Files Included
- `data`: Folder containing the dataset used for analysis.
- `analysis.ipynb`: Jupyter Notebook containing the Python code for the analysis.
- `README.md`: This file, providing an overview of the analysis and instructions.

## Instructions
To replicate the analysis or further explore the dataset, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have the necessary dependencies installed. You can install them using `pip install -r requirements.txt`.
3. Open `analysis.ipynb` using Jupyter Notebook or JupyterLab.
4. Follow the instructions and code cells in the notebook to reproduce the analysis.

## Dependencies
- Python 3.x
- Pandas
- Matplotlib
- Scipy
- Jupyter Notebook

## References
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/version/0.25.0/reference/api/pandas.core.groupby.GroupBy.mean.html)
- [Matplotlib Documentation](https://matplotlib.org/2.1.1/api/_as_gen/matplotlib.pyplot.plot.html)
- [Matplotlib Colors Documentation](https://matplotlib.org/stable/users/explain/colors/colors.html)

## Observations

Based on the figures and tables generated, here are some observations:

- There is a strong positive correlation of 0.84 between mouse weight and the average tumor volume.
- Of the four drugs sorted by volume, Infubinol was the only drug with an outlier according to the box plots.
- The bar chart showed Capomulin to have the most observations with over 200 timepoints and Ramicane was a close second.

## Contributors
- Frewoini Mebrahtu
- Lucinda Hodgeson and Eric Johnson
