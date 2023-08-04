# Iris Species PCA Analysis

## Introduction

This project utilizes Principal Component Analysis (PCA) to reduce the dimensionality of the Iris dataset(You can access the dataset by clicking [here](https://www.kaggle.com/datasets/uciml/iris)). By converting the data from 4 dimensions to 2, we can visualize the differences between the three species of Iris flowers (Setosa, Virginica, and Versicolor).

## Requirements

- NumPy
- Pandas
- Matplotlib
- scikit-learn

## Code Description

1. **Import Libraries:** Necessary libraries for data handling and visualization are imported.
2. **Data Loading & Preprocessing:** The Iris dataset is loaded and unnecessary 'Id' column is dropped.
3. **Feature & Target Definition:** Features and target variable are separated.
4. **Feature Scaling:** The features are standardized to give them equal weight in the PCA analysis.
5. **PCA Application:** PCA is performed, reducing the features from 4 dimensions to 2.
6. **Creating the Principal Components DataFrame:** A DataFrame containing the first two principal components is created and concatenated with the species information.
7. **Visualization:** A scatter plot is created to visualize the data distribution among the different species.
8. **Professional Plotting:** A more professional-looking plot is created using different colors for each species.
9. **Explained Variance Ratio:** The percentage of the total variance in the dataset explained by the first two principal components is printed.
10. **Total Explained Variance:** The sum of the explained variance by the first two principal components is printed.

## Conclusion

The code provides an easy and efficient way to visualize the Iris dataset using PCA. By reducing the dimensionality, it helps in understanding the variance among different species and could be a precursor step for classification tasks.

