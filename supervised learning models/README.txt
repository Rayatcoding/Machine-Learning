This project explores the performance of supervised learning models on two datasets using deep neural networks (DNN), k-nearest neighbors (KNN), and support vector machines (SVM). The implementation is provided in Jupyter notebooks.

Overleaf READ-ONLY link:
https://www.overleaf.com/read/xmqypyzbxjys#caf8c4

Github link repository:
https://github.gatech.edu/gt-omscs-ml/cs-7641-2025-spring-ylei82/tree/b94c58c4fffa823d96d3cdd211ebeeac506460da/Assignment-1

Code Structure
-A1_code.ipynb: process spotify dataset.
  - Creates directories: `NN/`, `KNN/`, `SVM/`, `Model_Comparison/`
  - Saves logs and images in the respective folders.
  - Please run all cells in sequence to avoid potential errors
-A1_code_part2.ipynb: process customer personality dataset.
  - Creates directories: `customer_NN/`, `customer_KNN/`, `customer_SVM/`, `customer_Model_Comparison/`
  - Saves logs and images in the respective folders.
  - Please run all cells in sequence to avoid potential errors

Required dependencies:
-numpy
-pandas
-scikit-learn
-matplotlib
-tensorflow
-torch
-random
-time
-os

Note:
1. please make sure the .ipynb files are at same directory with the (dataset) .csv file otherwise it will not able to find the data to process.
