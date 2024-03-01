# Sensitivity analysis of distributed photovoltaic system capacity estimation based on artificial neural network

This repository contains the files and code used to produce results presented in "Sensitivity analysis of distributed photovoltaic system capacity estimation based on artificial neural network", co-authored by Lingxi Tang, Masao Ashtine, Weiqi Hua and David Wallom.

The descriptions of each file are written below. 


## Jupyter Notebooks

Training Dataset Creation.ipynb
*(See Section 3.3)* 
- Extracts averaged 24-hour net load curve from each week in an annual time-series dataset and subsequently extracts IFEEL features to create the dataset with training and testing samples

Feeder Net Load Data Analysis.ipynb
*(See Figure 3)* 
- Plots average 24-hour net load curve of specific season and intra-week groups

Hyperparameter Optimisation.ipynb
*(See Sections 3.1 and 4.1)* 
- This set of code was used to optimise hyperparameters for the ANN. 

Season/Intra-week group Sensitivity Analysis.ipynb
*(See Section 4.2)*
- This set of code was used to perform algorithm sensitivity analysis to season and intra-week group of data samples. 

No. of households Sensitivity Analysis.ipynb
*(See Sections 4.2.4)*
- This set of code was used to perform algorithm sensitivity analysis to number of households associated with the substation feeder

Functions.ipnyb
- Contains Python functions used in scripts mentioned above

## Files

IFEEL_test_data_1month_30mins.csv
- Imported in some notebookes above for its column headings

Load + PV Dataset.csv
- Time-series data at 30min resolution
- 162 individual household load consumption data, in kW
- PV generation data 

Training datasets
- ML-ready datasets of input features (14 IFEEL features + season + intra-week group) and output label

