Dynamic Conditional Correlation (DCC) Model for High-Dimensional Financial Data
This repository contains the implementation of a Dynamic Conditional Correlation (DCC) Model combined with Principal Component Analysis (PCA) to estimate time-varying covariance matrices in high-dimensional financial data. The model reduces dimensionality, captures dependencies between assets, and improves performance in applications like portfolio optimisation and risk management.

Features
Dimensionality Reduction: Implements PCA to reduce the dimensionality of large financial datasets.
Dynamic Correlations: Utilises the DCC model to estimate time-varying correlations across assets.
Financial Applications: Outperforms standard methods in tasks like portfolio construction by improving covariance matrix estimation.
Python Implementation: Built using efficient Python libraries for numerical computation and data analysis.

Acknowledgements
This project uses the Geometric-Inverse Shrinkage (GIS) estimator code by Patrick Ledoit (available at https://www.econ.uzh.ch/en/people/faculty/wolf/publications.html#Programming_Code). The GIS method is employed for improved covariance matrix estimation.
