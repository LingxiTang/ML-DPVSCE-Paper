# Distributed Photovoltaic System Capacity Estimation using Feeder Load Data based on Deep Learning

This repository contains the files and code used to produce results presented in "Distributed Photovoltaic System Capacity Estimation using Feeder Load Data based on Machine Learning" by Lingxi Tang.

Refer to report for description and purpose of each script. 

The descriptions of each notebook and file are written below. 


## Jupyter Notebooks

Activation Functions Plot.ipynb
*(See Section 2.2)*
- Plot Fig. 2.2b

Training Dataset Creation.ipynb
*(See Section 4.2)* 
- Extracts averaged 24-hour net load curve from each week in an annual time-series dataset and subsequently extracts IFEEL features to create the dataset with training and testing samples

Feeder Net Load Data Analysis.ipynb
*(See Section 4.3)* 
- Plots average 24-hour net load curve of specific season and intra-week groups

Hyperparameter Optimisation.ipynb
*(See Sections 5.1 and 6.1)* 
- This set of code was used to optimise hyperparameters for the ANN. 

Season/Intra-week group Sensitivity Analysis.ipynb
*(See Sections 5.2.1, 5.2.2, 5.2.3, 6.2.1, 6.2.2, 6.2.3)*
- This set of code was used to perform algorithm sensitivity analysis to season and intra-week group of data samples. 

No. of households Sensitivity Analysis.ipynb
*(See Sections 5.2.4 and 6.2.4)*
- This set of code was used to perform algorithm sensitivity analysis to number of households associated with the substation feeder

Functions.ipnyb
- Contains Python functions used in scripts mentioned above

## Files

Histogram.xlsx
*(See Fig. 2.4b)*

IFEEL_test_data_1month_30mins.csv
- Imported in some notebookes above for its column headings

Load + PV Dataset.csv
- Time-series data at 30min resolution
- 162 individual household load consumption data, in kW
- PV generation data 


