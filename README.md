# Wine Quality Analysis and Prediction

This project aims to analyze and predict the quality of wines based on their chemical properties using various statistical and machine learning techniques. The dataset used for this analysis is the Wine Quality dataset, which includes multiple physicochemical properties of different wine samples and their corresponding quality scores.

## Objectives

1. **Data Exploration**:
   - Perform initial data exploration to understand the distribution and relationships of the variables in the dataset.
   
2. **Statistical Analysis**:
   - Conduct statistical analyses to identify significant predictors of wine quality.
   - Use linear regression to model the relationship between wine quality and its chemical properties.
   
3. **Principal Component Analysis (PCA)**:
   - Perform PCA to reduce the dimensionality of the dataset while retaining most of the variance.
   - Visualize the projection of the data onto the first two principal components to uncover underlying patterns.
   
4. **Correlation Analysis**:
   - Compute and visualize the correlation matrix to identify relationships between different chemical properties.
   
5. **Model Interpretation**:
   - Interpret the results of the regression and PCA to gain insights into the factors influencing wine quality.

## Dataset

The Wine Quality dataset includes the following variables:
- **Fixed Acidity**
- **Volatile Acidity**
- **Citric Acid**
- **Residual Sugar**
- **Chlorides**
- **Free Sulfur Dioxide**
- **Total Sulfur Dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**
- **Quality (Target Variable)**

## Key Findings

- **Linear Regression**: Identified significant predictors of wine quality, with alcohol content and volatile acidity being key factors.
- **Principal Component Analysis**: Revealed that the first two principal components capture a significant portion of the variance in the data, highlighting important underlying patterns.
- **Correlation Analysis**: Showed strong correlations between certain chemical properties, such as fixed acidity and citric acid, and provided insights into their relationships with wine quality.

## Visualization

- **Correlation Matrix**: Visualized the pairwise correlations between variables to understand their relationships.
- **PCA Projection**: Displayed the projection of wine samples onto the first two principal components, showing clustering of different quality scores.

## Conclusion

This project provides a comprehensive analysis of the Wine Quality dataset, using statistical and machine learning techniques to understand the factors that influence wine quality. The insights gained from this analysis can help winemakers optimize their production processes to improve wine quality.

## How to Run

1. Clone the repository:
   ```sh
   git clone https://github.com/edvardghukasyan/MultivariateStatisticsProject.git
