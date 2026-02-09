📄 README – PCA Formative Assignment

Student: Vestine Umukundwa
Notebook: formative1_vestine UMUKUNDWA.ipynb
Dataset: price_of_healthy_diet_clean.csv

Project Description:
This project applies Principal Component Analysis (PCA) to a real-world dataset focused on food affordability in African contexts.

PCA is used to:
-reduce dimensionality
-remove redundant information
-retain the most important patterns
-improve visualization and analysis

Dataset
The data includes country-level indicators such as:

-Cost of a healthy diet
-annual diet cost
-vegetable and fruit costs
-total food component cost
-Only numerical variables are used for PCA.

⚙️ Steps
1)Load and standardize the data
2)Compute the covariance matrix
3)Perform eigendecomposition
4)Sort principal components
5)Project data onto selected PCs
6)Output reduced data
7)Visualize before and after PCA

Key Results
PC1: ~39.7%
PC2: ~29.2%
PC3: ~14.3%
 =The first 3 components explain over 83% of the total variance.
What We Learned

PCA helps to:
-simplify complex datasets
-reduce noise
-support faster analysis
-visualize high-dimensional data

 How to Run

Upload the dataset
Run cells sequentially
Ensure outputs are displayed

Libraries:
pandas
numpy
matplotlib
