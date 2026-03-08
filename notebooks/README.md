# Notebooks

This folder contains the Jupyter lab notebooks used to develop the PulsePredictor project.  
Each notebook represents a stage in the data science workflow from data ingestion to model development.

## Notebook Overview

1. **01_load_and_extract.ipynb**

   Loads the raw BRFSS 2021 dataset (.XPT format) and converts it into a workable format for analysis.
   
   Key tasks:
   - Importing the dataset
   - Converting XPT to CSV
   - Initial dataset inspection
   - Basic dataset validation

---

2. **02_eda.ipynb**

   Performs exploratory data analysis (EDA) to understand relationships between variables and identify patterns related to depression risk.

   Key tasks:
   - Data cleaning
   - Feature selection
   - Handling missing values
   - Correlation analysis
   - Visualization of key predictors

---

3. **03_modelling_notebook_v1.0.ipynb**

   Builds and evaluates machine learning models to predict depression risk.

   Key tasks:
   - Train-test split
   - Feature engineering
   - Model training
   - Model comparison
   - Evaluation using metrics such as Accuracy, Precision, Recall, F1-score, and AUC

### Recommended Execution Order

1. 01_load_and_extract.ipynb  
2. 02_eda.ipynb  
3. 03_modelling_notebook_v1.0.ipynb


