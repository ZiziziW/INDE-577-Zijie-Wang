# Principal Component Analysis
Main content of Principal Component Analysis
* [Principal Component Analysis] Jupyter notebook file
* Data set: The penguin dataset
## Introduction 
PCA is utilized in exploratory data analysis and predictive model development. It's often used for dimensionality reduction, where each data point is projected onto only the first few principal components to produce lower-dimensional data while keeping as much variance as feasible. The starting point of PCA is the matrix of correlation coefficients derived from the original data set. Strictly speaking, the rationale behind the method requires that the correlations be obtained from variables measured on some continuous scale. 
![image](https://user-images.githubusercontent.com/90750119/166845454-4ff6d4e9-c068-451b-9839-d55dc6d29236.png)

## Singular value decomposition
The principal components transformation can also be associated with another matrix factorization, the singular value decomposition (SVD) of X:
![image](https://user-images.githubusercontent.com/90750119/166845163-a3eccfa9-f9d4-486c-9823-10b7a2d39cc4.png)

## Data set
### penguins
To illustrate this point, let us import the following packages, load the penguins dataset, and show data related with the bill_length versus bill_depth.

**Bill dimensions**
The culmen is the upper ridge of a bird’s bill. In the simplified penguins data, culmen length and depth are renamed as variables bill_length_mm and bill_depth_mm to be more intuitive.

**flipper_length_mm**: flipper length (mm)

**body_mass_g**: body mass (g)

**island**: island name (Dream, Torgersen, or Biscoe) in the Palmer Archipelago (Antarctica)

**sex**: penguin sex

### load_breast_cancer
Features
This is a binary classification dataset.

It has no Missing attribute or Null values.

The class distribution is as follows.

212: malignant
357: benign
This is a commonly used dataset. Machine learning papers have also used this dataset to address regression problems.

All the data types are numerical.

# Reference
Principal component analysis,https://en.wikipedia.org/wiki/Principal_component_analysis

Covariance and correlation,https://en.wikipedia.org/wiki/Covariance_and_correlation

In Depth: Principal Component Analysis,https://jakevdp.github.io/PythonDataScienceHandbook/05.09-principal-component-analysis.html

\International Encyclopedia of Education (Third Edition), 2010, Principal Component Analysis,https://www.sciencedirect.com/topics/medicine-and-dentistry/principal-component-analysis
