# w-ML
 Machine learning for anomaly detection in water data.

# Multivariate functional data analysis and machine learning methods for anomaly detection in water quality data
 This repository containes the code corresponding to the machine learning part of the research paper entitled "Multivariate functional data analysis and machine learning methods for anomaly detection in water quality data" and authored by Xurxo Rigueira, David Olivieri, Maria Araujo, Angeles Saavedra and Maria Pazo.
 <p align="center">
  <img src="https://github.com/xrigueira/w-fda/blob/main/plots/graphical_abstract.pdf" />
 </p>

## Requirements
To run the code in this repository, you need the following libraries and tools:

- Python 3.9.x
- NumPy
- pandas
- scikit-learn
- matplotlib

## Citation
If you find this repository useful in your research, please consider citing the following paper:

```
@article{Rigueira2025,
    title={Multivariate functional data analysis and machine learning methods for anomaly detection in water quality data},
    author={Xurxo Rigueira and David Olivieri and Maria Araujo and Angeles Saavedra and Maria Pazo},
    journal={},
    volume={}
    year={2025},
    doi={}
    issn={}
}
```

## Structure
The repository contains the following relevant directories and files:

```
w-fda
   |-- data: preprocessed data.
   |-- preprocessors: code to preprocess the raw data.
   |-- results: prediction results and code to analyze and plot them.
   |-- raw-data: original data before preprocessing.
```

## Overview of relevant files and usage

* `preprocessing.py`: call to the preprocessors to join all variables in a single database, perform labelling, imputation, and smoothing.
* `grid_search_optim`: Grid Search tuning of window size and stride.
* `main.py`: main file to obtain resutls with the ML learning models.