# Flight-Data-Preprocessing

## Overview  
This project focuses on cleaning and preprocessing a flight price dataset, including handling missing values, detecting and treating outliers, and encoding categorical variables.

## Data Preprocessing Steps  

### 1. Import Libraries & Load Dataset  
- Used `pandas`, `numpy`, `seaborn`, `matplotlib`, and `sklearn.preprocessing` for data processing.  
- Loaded the dataset and explored its structure using `info()`, `head()`, and `describe()` functions.  

### 2. Handling Missing Values  
- Checked for missing values in the dataset.

### 3. Detecting & Handling Outliers  
- Used the **Interquartile Range (IQR) method** to detect outliers in `Duration` and `Price` columns.  
- Applied **capping** to replace extreme values within acceptable limits.  

### 4. Encoding Categorical Variables  
- **Label Encoding** applied to categorical columns.  
- **Mapping Encoding**

  ### Data Set:
  [Here](https://www.kaggle.com/datasets/orhfusion/flight-price-dataset)
