#  Yield Grade Analytics
This dataset contains information about various attributes of a set of fruits, providing insights into their characteristics. 
The dataset includes details such as fruit ID, size, weight, sweetness, crunchiness, juiciness, ripeness, acidity, and quality.


# Dataset
The dataset contains the following attributes:

Size: The size of the apple.
Weight: The weight of the apple.
Sweetness: The sweetness level of the apple.
Crunchiness: The crunchiness level of the apple.
Juiciness: The juiciness level of the apple.
Ripeness: The ripeness level of the apple.
Acidity: The acidity level of the apple.
Quality: The quality of the apple, where True indicates a good apple and False indicates a bad apple.
The dataset is split into two parts:

Analysis
Exploratory Data Analysis (EDA)
Histograms

Plotted histograms for Crunchiness, Sweetness, Weight, and Size for both good and bad apples to visualize their distributions.
Distribution Diagrams

Created Kernel Density Estimate (KDE) plots for good and bad apples to understand the distribution of attributes.
Correlation Analysis

Computed and visualized the correlation matrix for the numeric attributes to identify relationships between them.
Boxplots

Generated boxplots to visualize the distribution and potential outliers in the attributes.
## Statistical Tests
# Levene's Test

Performed Levene's test for equality of variances for each attribute to check if variances between good and bad apples are significantly different.
# Two-Sample T-Test

Conducted independent two-sample t-tests to determine if there are significant differences in the means of attributes between good and bad apples.
Machine Learning
# K-Nearest Neighbors (KNN)

Trained a KNN classifier to predict apple quality. The model achieved an accuracy of approximately 89.6%.
# Random Forest

Trained a Random Forest classifier to predict apple quality. The model achieved an accuracy of approximately 88.5%.
# Classification Report

Generated classification reports and visualized them using heatmaps to assess model performance.

# Conclusion
The analysis reveals key differences between good and bad apples based on their attributes. Significant differences were found in weight, size, sweetness, and juiciness. Machine learning models, including KNN and Random Forest, show good performance in classifying apples based on these attributes.

# Future Work
Feature Engineering: Explore additional features or transformations to improve model performance.
Model Tuning: Experiment with hyperparameter tuning for better accuracy.
Cross-Validation: Implement cross-validation to ensure the robustness of the models.
# References
Matplotlib Documentation
Seaborn Documentation
Scikit-learn Documentation
SciPy Documentation
