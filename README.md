Student: Vestine Umukundwa
Notebook: formative1_vestine UMUKUNDWA.ipynb
Dataset: price_of_healthy_diet_clean.csv

📌 Project Description

This project implements Principal Component Analysis (PCA) using a real-world dataset adapted to African contexts.

The goal of PCA is to:

reduce dimensionality

remove redundancy

keep the most important information

make data easier to visualize and analyze

📊 Dataset Information

The dataset contains country-level food price indicators such as:

cost of a healthy diet

annual cost

vegetables cost

fruits cost

total food component cost

Both numerical and categorical variables are present.

Step 1: Load and Standardize the Data
# Step 3: Calculate the Covariance Matrix
# Step 4: Perform Eigendecomposition
# Step 5: Sort Principal Components
# Step 6: Project Data onto Principal Components
# Step 7: Output the Reduced Data
Step 8: Visualize Before and After PCA

Key Results

PC1 explains ~39.7% of variance

PC2 explains ~29.2%

PC3 explains ~14.3%

👉 Together, the first 3 PCs explain over 83% of the total information.

🧠 What We Learned

PCA helps to:

✔ simplify complex datasets
✔ reduce noise
✔ speed up machine learning
✔ visualize multi-dimensional data

▶️ How to Run

Upload the dataset into the notebook directory

Run cells from top to bottom

Ensure outputs are visible

Submit the notebook

🛠 Libraries Used

pandas

numpy

matplotlib



Colab paid products - Cancel contracts here
data = pd.read_csv("price_of_healthy_diet_clean.csv")
