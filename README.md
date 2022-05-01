# Distributed Photovoltaic System Capacity Estimation using Feeder Load Data based on Deep Learning

This repository contains the files and codes used to produce results presented in "Distributed Photovoltaic System Capacity Estimation using Feeder Load Data based on Deep Learning" by Lingxi Tang.

Refer to report for description and purpose of code. 

The descriptions of each code and file are written below. 


## Codes

Feeder Net Load Data Analysis.ipynb
- (See Section 4.2) 
- Plots average 24-hour net load curve of specific season and intra-week groups

Training Dataset Creation.ipynb
- Extracts averaged 24-hour net load curve from each week in an annual time-series dataset and subsequently extracts IFEEL features to create the dataset with training and testing samples

Hyperparameter Optimisation.ipynb
- (See Sections 5.1 and 6.1) 
- This set of code was used to optimise hyperparameters for the ANN. 

Season/Intra-week group Sensitivity Analysis.ipynb
- (See Sections 5.2.1, 5.2.2, 6.2.1, 6.2.2, 6.2.3)
- This set of code was used to perform algorithm sensitivity analysis to season and intra-week group of data samples. 

No. of households Sensitivity Analysis.ipynb
- (See Sections 5.2.3 and 6.2.4)
- This set of code was used to perform algorithm sensitivity analysis to number of households associated with the substation feeder

Functions.ipnyb
- Contains Python functions used in codes mentioned above

## Training Datasets
- 2 csv files which contain all samples, each with 16 input features and 1 output variable


## Results
- .npy files which can be loaded by codes above to be plotted

## Files

Histogram.xlsx
- (See Fig. 3.4b)

IFEEL_test_data_1month_30mins.csv
- Imported in some codes above for its column headings

Load + PV Dataset.csv
- Time-series data at 30min resolution from year 2013
- Individual household load consumption data
- PV generation data 
- Provided by Dr. Bruce Stephen


