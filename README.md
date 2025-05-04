# Principles of Data Analytics

by Philip Cullen

## Project Overview

This project uses several different tools and packages to analyse the Iris Dataset.

The Iris Dataset is taken from the 1936 paper, *The Use of Multiple Measurements in Taxonomic Problems* (1) by Robert A. Fisher. 
The dataset is imported from scikit-learn.org (2).

## Paper Summary
The data for this project original comes from "The Use of Multiple Measuremanets in Taxonomic Problems" by R. A. Fisher. The paper written in 1936, serves as a foundation for multivariate statisitcs. In the paper, Fisher took measured the morphology of three different varients of the Iris flower. The Iris flowers used in the study were Iris setosa, Iris versicolor, and Iris virginica. He measured the petal length (cm), petal width (cm), sepal length (cm), and the sepal width (cm). The overall goal was to ascertain if these measurements could be used to reliably claffify each different species of flower. Fisher was then able to develop a statiscal method, linear discriminant. Utilising this method one can identify a combination of features for two or more objects while retaining the ability to accurately discriminate between them.

### Why this is relevant to data analytics
Fisher's linear discrimiant statistical model served as the foundation for Linear Disciminant Analysis (LDA), also known as normal discriminant analysis (NDA) or discriminant function analysis (DFA). This enables analysts to visually explore, represent, and classify data. This model is used in machine learning, bioinformatics, financial modeling, and pattern recognicition. This allows analysts to take large complex datasets and simplify them while still preserving each classes unique information. By doing this it allows for better visualisation and interpretation of highly complex datsets.

## Technologies
- Python
- Git
- GitHub
- Codespaces
- Jupyter

## Packages
- matplotlib (Used for the plotting and visualising of data)
- numpy (Used tp create a numpy array to allow numpy functions to be used on the data for calculations)
- pandas 
- sklearn (required to import the dataset)
- seaborn

## Relavant Links/References
1) https://onlinelibrary.wiley.com/doi/epdf/10.1111/j.1469-1809.1936.tb02137.x
2) https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_iris.html
3) https://gist.githubusercontent.com/netj/8836201/raw/6f9306ad21398ea43cba4f7d537619d0e07d5ae3/iris.csv
