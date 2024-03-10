# Socioeconomic Index Construction with PCA

This project explores the construction of a socioeconomic index using Principal Component Analysis (PCA) applied to a household sample dataset from the Demographic and Health Surveys (DHS). The objective is to create a wealth index that reflects the economic status of households based on their ownership of various assets.

## Background

PCA is a statistical technique commonly used to identify underlying patterns and capture the most significant sources of variation in data. In the context of socioeconomic analysis, PCA is particularly useful for constructing wealth indices because it can handle datasets where asset variables are correlated and where the distribution of variables varies across cases, such as households.

## Methodology

In this project, we apply PCA to the DHS household dataset to create a wealth index. We leverage the correlation between asset variables and the variation in their distribution across households to extract the most informative components. Assets that are more unequally distributed among households are given greater weight in the PCA process, ensuring that the resulting wealth index adequately represents the multidimensional aspects of socioeconomic status (SES).

## Implementation

The project utilizes R programming language for data analysis and visualization. We employ the `princomp()` function from the `stats` package to perform PCA on the dataset. Subsequently, we assess the contribution of variables to the first principal component using the `fviz_cos2()` function. We also construct a scree plot using `fviz_eig()` to determine the number of principal components needed to retain most of the variance in the dataset.

## Results and Interpretation

The project categorizes households into broad socioeconomic categories, such as 'Poor', 'Middle', and 'Rich', based on the scores derived from PCA. Cutoff points for categorization are determined either arbitrarily or using quintiles, with the latter approach ensuring a more uniform distribution of socioeconomic scores across groups.

## installation
Click and download the html file to view the step by step process

