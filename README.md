# Data Imputation Using k-Nearest Neighbors (KNN)

## Overview
This project demonstrates the use of **k-Nearest Neighbors (KNN) Imputation** to handle missing values in a dataset. The approach selects the most similar data points based on non-missing values and imputes missing values accordingly.

## Methodology
1. **Data Cleaning**:
   - Non-numeric columns are excluded from imputation.
   - Missing values are identified and analyzed.

2. **Imputation Using KNN**:
   - The `KNNImputer` from `sklearn.impute` is used.
   - Each missing value is replaced by the mean of its **k-nearest neighbors** (where `k=3` in this case).

3. **Visualization**:
   - The imputed dataset is compared against the original dataset.
   - Line plots for each feature illustrate the difference between observed and imputed values.

## Setup & Execution
### **Prerequisites**
- Python 3.x
- Libraries: `pandas`, `matplotlib`, `sklearn`
- Dataset (`data.csv`) in the project directory.

### **Steps to Run**
1. Install required libraries:
   ```bash
   pip install pandas matplotlib scikit-learn
  ```
