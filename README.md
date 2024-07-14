# Heart_disease_prediction_SVM

## Insights

The analysis provides insights into the distribution of heart disease risk factors, the presence of missing data, potential outliers, and correlations between variables. These insights can be valuable for further research and model development.


## Notebook Overview

The notebook performs the following steps:

1. **Data Loading:** Loads heart disease datasets from CSV files into Pandas DataFrames.

2. **Data Concatenation:** Combines the three datasets into a single DataFrame.

3. **Data Cleaning:** Removes irrelevant columns ('ca', 'slope', 'thal') and replaces missing values ('?') with NaN.

4. **Missing Data Detection:** Uses the `missingno` library to visualize missing data patterns.

5. **Outlier Detection and Class Imbalance:** Employ Seaborn boxplots to identify outliers and assess class imbalance in the 'heartdisease' variable

6. **Correlation Analysis:** Generates a heatmap using Seaborn to visualize correlations between variables.

7. **Train-Test Split:** Split the data into training and testing sets (70% training, 30% testing).
  
8. **Scaling:** Standardize the features using StandardScaler.
  
9. **Model Training:** Train a Support Vector Machine (SVM) classifier with a radial basis function (RBF) kernel.
 
10. **Prediction:** Predict heart disease on the test set.
 
11. **Evaluation:** Calculate the accuracy score of the model.



## Libraries Used
- NumPy

- Pandas

- Missingno

- Matplotlib

- Seaborn

- Sklearn


## How to Use

1. Open the notebook in Google Colab.
2. Ensure that the CSV files (cleveland_heart_disease.csv, hungarian_heart_disease.csv, swiss_heart_disease.csv) are accessible in the Colab environment.
3. Run each code cell sequentially to execute the analysis.


