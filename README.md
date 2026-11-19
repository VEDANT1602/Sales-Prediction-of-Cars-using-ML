# Predicting used-car prices

**Divyesh Rathod, Meet Shah and Vedant Thaker · Arizona State University**

The target was the price of an individual used car. The team report describes 20,063 vehicle records with 11 features and compares regression approaches across a local computer, Google Colab and AWS SageMaker. [Read the original report](STP598Project.pdf).

Pages 12 and 17 give a useful comparison. K-nearest neighbors had a reported R² of 0.93. Random forest with PCA had a reported R² of 0.98. Those values come from the team’s original evaluation. The PDF also reports mean absolute error and discusses differences in training time across environments.

This repository preserves the report. The training scripts, dataset and run environment would be needed to reproduce the numbers independently.

