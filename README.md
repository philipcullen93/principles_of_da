# Principles of Data Analytics

by Philip Cullen

## Within this Repository:
Within this repository are the following files:
- tasks.ipynb
- README.md
- .gitignore

## Table of Contents
- Project Overview
- Paper Summary
- Why This Project is Useful
- Technologies
- Packages
- Relevant Links/References

## Project Overview

This project uses several different tools and packages to analyse the Iris Dataset.

The Iris Dataset is taken from the 1936 paper, *The Use of Multiple Measurements in Taxonomic Problems* (1) by Robert A. Fisher. 
The dataset is imported from scikit-learn.org (2).

## Paper Summary
The data for this project original comes from "The Use of Multiple Measuremanets in Taxonomic Problems" by R. A. Fisher. The paper written in 1936, serves as a foundation for multivariate statisitcs. In the paper, Fisher took measured the morphology of three different varients of the Iris flower. The Iris flowers used in the study were Iris setosa, Iris versicolor, and Iris virginica. He measured the petal length (cm), petal width (cm), sepal length (cm), and the sepal width (cm). The overall goal was to ascertain if these measurements could be used to reliably claffify each different species of flower. Fisher was then able to develop a statiscal method, linear discriminant. Utilising this method one can identify a combination of features for two or more objects while retaining the ability to accurately discriminate between them. [1]

### Why this is relevant to data analytics
Fisher's linear discrimiant statistical model served as the foundation for Linear Disciminant Analysis (LDA), also known as normal discriminant analysis (NDA) or discriminant function analysis (DFA). This enables analysts to visually explore, represent, and classify data. This model is used in machine learning, bioinformatics, financial modeling, and pattern recognicition. This allows analysts to take large complex datasets and simplify them while still preserving each classes unique information. By doing this it allows for better visualisation and interpretation of highly complex datsets. [2]

## Why this project is useful
This project allows the user to see the different steps one can use to visualise and interpret data. To do this, it uses scatter plots, histograms, boxplots, heatmaps and pairplots. These combined with tools such as regression lines and data corelation can further enhancce the users ability to make reasonable observations about the data with is further helped with the addition of the aforementioned plots. Additionally, it provides the user with code that could be used to analyse different datasets. 

## How to Run the tasks.ipynb File
1) Download the tasks.ipynb file from the repository or clone the repository onto your computer (see below)

2) Launch Jupyter Notebook by typing jupyter notebook in the command prompt (Windows) or terminal (Mac/Linux).

3) Navigate to the directory where the ipynb file is located.

4) Click on the ipynb file to open it in Jupyter Notebook.

## How to clone the Repository
1) Copy the following URL: https://github.com/philipcullen93/principles_of_da.git

2) Click on the “<> Code ” button and copy the URL under HTTPS.

3) Open VsCode and press “ Ctrl+` ” on your keyboard to open the terminal.

4) Type “git clone ” then press ” Spacebar ” and paste the URL  which you have copied in the earlier step into the terminal.

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

## Relevant Links/References
The following are a list of references found in the README.md file.
1) Source of the Paper "The Use of Multiple Measuremanets in Taxonomic Problems" by R. A. Fisher: https://onlinelibrary.wiley.com/doi/epdf/10.1111/j.1469-1809.1936.tb02137.x
2) Linear Discrimination Analysis: https://www.ibm.com/think/topics/linear-discriminant-analysis#:~:text=Linear%20discriminant%20analysis%20(LDA)%20is,helps%20optimize%20machine%20learning%20models.

The following are a list of references found within the Jupyter Notebook.
1) Loading the Iris Dataset: https://scikit-learn.org/stable/datasets/toy_dataset.html
2) Using the print function : https://realpython.com/python-print/
3) Creating a Panda DataFrame: https://www.w3schools.com/python/pandas/pandas_dataframes.asp
4) Python Arrays: https://www.w3schools.com/python/python_arrays.asp
5) Creating Python Variables: https://www.w3schools.com/python/python_variables.asp
6) Source of csv file: https://gist.githubusercontent.com/netj/8836201/raw/6f9306ad21398ea43cba4f7d537619d0e07d5ae3/iris.csv
7) Numpy Array Creation: https://numpy.org/doc/stable/user/basics.creation.html
8) Python for Loops: https://www.w3schools.com/python/python_for_loops.asp
9) Numpy Mean: https://docs.vultr.com/python/third-party/numpy/mean
10) Numpy Minimum: https://docs.vultr.com/python/third-party/numpy/minimum
11) Numpy Maximum: https://docs.vultr.com/python/third-party/numpy/maximum
12) Numpy Standard Deviation: https://docs.vultr.com/python/third-party/numpy/std
13) Numpy Median: https://docs.vultr.com/python/third-party/numpy/median
14) Plotting Histograms using Matplotlib.pyplot: https://www.geeksforgeeks.org/plotting-histogram-in-python-using-matplotlib/
15) Using Matplotlib.pyplot to Create Scatter Plots: https://www.w3schools.com/python/matplotlib_scatter.asp
16) Adding a Linear Regression Line using numpy.polyfit: https://www.w3schools.com/python/numpy/numpy_polynomial.asp
17) Creating Boxplots in Python: https://www.datacamp.com/tutorial/python-boxplots
18) Corelations in Panda: https://www.w3schools.com/python/pandas/pandas_correlations.asp#:~:text=Finding%20Relationships,column%20in%20your%20data%20set.
19) Creating a Heatmap using Matplotlib: https://matplotlib.org/stable/gallery/images_contours_and_fields/image_annotated_heatmap.html
20) Analysing Heatmaps: https://medium.com/@kulkarni.madhwaraj/heatmap-analysis-using-python-seaborn-and-matplotlib-f6f5d7da2f64
21) Linear regression Using Numpy: https://realpython.com/linear-regression-in-python/
22) Loading Datasets using Seaborn: https://seaborn.pydata.org/generated/seaborn.load_dataset.html
23) Using Custom Palettes in Seaborn: https://seaborn.pydata.org/tutorial/color_palettes.html
24) Creating a Pairplot using Seaborn: https://seaborn.pydata.org/generated/seaborn.pairplot.html
