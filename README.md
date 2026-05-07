# Assignment 1 - ML Preprocessing
**Amani - Computer Engineering student**

In this assignment, I worked on the Kaggle House Prices dataset. The goal was to clean the data and do some feature engineering before building the model.

### What I did:
* **Cleaning:** I filled the missing values (NaN). For some columns like PoolQC, NaN just means the house has no pool, so I filled them with "None".
* **Outliers:** I checked the GrLivArea and removed the extreme houses that were outliers to make the model better.
* **Log Transform:** I used `np.log1p` on the SalePrice because the data was skewed.
* **Plots:** I made a heatmap for correlations and a bar plot to see the average price in each neighborhood (as requested).
* **Encoding:** Used One-Hot Encoding for categories and Label Encoding for quality features.

The code is organized in cells and I added comments to explain each step.

