Dry Bean Model Comparison Project
Dataset
Dry Bean Dataset from the UCI Machine Learning Repository.

Citation:

Koklu, M., and Ozkan, I. A. (2020). Dry Bean [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C50S4B

Models Compared
Logistic Regression
Decision Tree
Random Forest
Gradient Boosting
Results
Model	Accuracy
Random Forest	0.9218
Logistic Regression	0.9214
Gradient Boosting	0.9207
Decision Tree	0.8917
Recommendation
Random Forest achieved the highest accuracy. However, Logistic Regression achieved nearly identical performance while being simpler, faster, easier to explain, and easier to maintain. For an initial production prototype, Logistic Regression is recommended.

Clustering
K-Means clustering was applied without labels. The resulting clusters showed meaningful natural groupings within the bean measurements.

Reproducibility
Install required packages:

pip install pandas numpy matplotlib scikit-learn openpyxl