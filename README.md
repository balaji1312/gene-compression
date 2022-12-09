This repo contains the data, code, results and report for our project 'Gene compression using Machine Learning for
Cancer type Classification' for BIO ENG 275 - Machine Learning and Data-Driven Modeling in Bioengineering

## Authors: Natarajan Balaji Shankar, Shruti Mohanty, Sidarth Srinivasan

## Structure: 

### Code - 
1. ICA.ipynb - Performs ICA and Logistic Regression and calculates per class performance metrics and scores and loading plots
2. PCA.ipynb - Performs PCA and Logistic Regression and calculates per class performance metrics and scores and loading plots
3. NMF.ipynb - Performs NMF and Logistic Regression and calculates per class performance metrics and scores and loading plots
4. Comparisons.ipynb - Comparisons between the 3 algorithms in terms of performance and accuracy metrics, performs multiclass classifation using Logistic Regression, SVM Classification, K means Clustering and GMM Clustering and compares their accuracy and computation time
5. cross_validation.ipynb - Performs cross validation on the dataset for k=5 latent dimesnion followed by SVM, Logistic Regression. 

The goal of the first three notebooks is to measure data reduction efficiency across the different compression methods. Comparisons pits different compression and classification methods to determine the method with the hgihest accuracy. cross_validate aims to discover the efficacy of cross validation in estimating prediction error

### Data - 
Input train, test and label matrices were obtained from - https://github.com/greenelab/BioBombe/tree/master/0.expression-download/data

### Results - 
Results of the Code notebooks are stored in different subdirectories for accuracy plots, correlation box plots, binary classification accuracy results, comparison across algorithm plots. 

For more analysis on the results, please refer to the report - "BE275_ProjectReport.pdf"