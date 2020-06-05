# Prediction of Psychosis in Parkinson’s Patients using Machine learning - Master 2020

In order to run the notebooks the folders and csv files in "Necessary Folders and Files" must be downloaded and placed where you point the code to look for them

Notebooks 1,2 and 3 must be run in chronological order. 

Notebook 4 and 5 are dependant on data processed with the right flags in notebook 3

#### Notebook 1- Data Collection:
This notebook requires the PPMI database in "Necessary Folders and Files". Other than this, this notebook has no options available and can be run as it is

#### Notebook 2 - Missing Values:
This notebook is dependant on the csv file created in notebook 1. This notebook has one notable option that needs to be set with a flag, which is which missing value imputation that is to be used

#### Notebook 3 - Main Preprocessing:
This notebook is dependant on the output of notebook 2. This notebook has many different options which can be set by using the corresponding flags. The flags dictate how the data is processed for notebook 4 and 5. 

#### Notebook 4 - ML Models:
This notebook is dependant on the output of notebook 3. The data must have been processed in notebook 3 with the flag "LONGITUDINAL_APPROACH" set to either 0 or 1. Each model in notebook 4 has options available for it. The same is true for how we show final results for models. 

#### Notebook 5 - Deep Learning:
This notebook is dependant on the output of notebook 3. The data must have been processed in notebook 3 with the flag "LONGITUDINAL_APPROACH" set to 2. The notebook should be run in steps (set with flags) because each step is computationally expensive. 
