Wine Quality Prediction Project

Overview

This project aims to predict the quality of wine based on various attributes using machine learning models. The dataset used consists of two separate datasets for red and white wine samples from the UCI wine quality dataset.

Step 1: Selecting a Real-World Dataset

In this project, we chose the UCI wine quality dataset, which is widely used in machine learning and statistical analysis. It includes separate datasets for red and white wine samples.

Step 2: Data Preparation and Cleaning

2.1 Loading the Dataset
We loaded the white and red wine datasets into Jupyter notebook using Pandas.

2.2 Exploring Basic Information
We explored the basic information about the datasets, such as their size, data types, and the presence of missing values.

2.3 Handling Missing, Incorrect, and Invalid Data
We checked for missing values in the datasets and found that both datasets had no missing values.

2.4 Additional Steps
We merged the red and white wine datasets to create a larger and more diverse dataset. This step enabled us to perform a more comprehensive analysis of wine properties and their effects on quality.

Step 3: Exploratory Analysis and Visualization

We computed statistics for numeric columns and explored the distribution of numeric columns using histograms and boxplots. We also analyzed the relationship between various columns using heatmap and boxplot visualizations.

Step 4: Training and Evaluating Machine Learning Models

We trained and evaluated four different machine learning models: Support Vector Classifier (SVC), Gradient Boosting Classifier, Decision Tree Classifier, and Random Forest Classifier. For each model, we experimented with different combinations of attributes to determine their impact on prediction performance.

Step 5: Conclusion

5.1 Analysis
We derived several interesting insights from the analysis, including the correlation between wine attributes and quality. Among all four models, Random Forest Classifier showed the highest precision and accuracy.

5.2 Future Work
We outlined several ideas for future work, including investigating the effect of individual features on wine quality, exploring other data sources, comparing with other models, and fine-tuning the models.

Resources

Data Source: UCI Machine Learning Repository
