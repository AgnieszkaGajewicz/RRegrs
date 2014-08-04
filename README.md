RRegrs
======

eNanoMapper Developers |  [eNanoMapper Project] (http://www.enanomapper.net/)


The current tool is a collection of regression tools from R that could be used to search the best regression models for any dataset. The initial use of the script is aimed at finding QSAR models for chemoinformatics / nanotoxicology.

The full R script will contain: Loading dataset, Filter dataset, Scaling dataset, Feature selection, Regression models, Summary with top models, Statistics of the best model, etc.

The script will be modular in order to create flexible APIs.

The main authors are from the National Technical University of Athens (NTUA) and Maastricht University (UM) joining efforts for the EU eNanoMapper project.

The list of the methods that will be included contains:
- Basic LM
- GLM based on AIC
- PLS
- Lasso
- RBF
- SVM radial
- SVM linear
- Neural Networks
- SOM
- Recursive Feature Extraction (SVM-RFE)
