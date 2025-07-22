README

Overleaf READ-ONLY link:
https://www.overleaf.com/read/mydtfgbkgmdf#051bf6

Github link repository:
https://github.gatech.edu/gt-omscs-ml/cs-7641-2025-spring-ylei82/tree/2b86db54aa4e39213d01a21efebe9880ae2e4fd1


## Overview
This script performs data preprocessing, dimensionality reduction, clustering, and neural network training using the Spotify and Customer datasets. It produces various visualizations and saves the results in the current working directory.

## Requirements
To run this script, ensure that the following four data files are present in the same directory as the script:
- `train_processed.csv`
- `test_processed.csv`
- `customer_train.csv`
- `customer_test.csv`

## Dependencies
The script requires the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `torch`
- `scipy`

## Output
The script generates the following outputs:
- **Console logs**: Displays clustering metrics, PCA explained variance, ICA kurtosis, and reconstruction errors.
- **Images** (saved in the current directory):
  - `step1_clustering_result.png` - Initial clustering visualization.
  - `step2_dimension_reduction.png` - Visualizing different dimension reduction techniques.
  - `step3_clustering_after_dr.png` - Clustering results after dimension reduction.
  - `step4_5_nn_training_result.png` - Neural network training error curves.

## Notes
- The script assumes the datasets are already preprocessed.
- All outputs (figures and logs) are saved in the same directory where the script is executed.

