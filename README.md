# astra-ml-models

This repository contains benchmarking notebooks created by **Amey Chitnis** in support of the research conducted by **Alexander Klemp** at the **Institute of Data Science Foundations (E-21), Hamburg University of Technology (TUHH)**.

The project focuses on applying machine learning models to simulate and analyze forward and inverse mappings derived from ASTRA (A Space Charge Tracking Algorithm) simulation data.

## Contents

- **`notebooks/9a_benchmarking_forward_map.ipynb`**  
  Trains and evaluates models to predict downstream beam parameters from initial conditions (forward mapping).

- **`notebooks/9b_benchmarking_inverse_map.ipynb`**  
  Trains and evaluates models to infer initial beam parameters from resulting beam characteristics (inverse mapping).

- **`data/`**  
  Contains preprocessed datasets used for model training and evaluation.


## Requirements

The notebooks rely on the following Python packages:

- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost  
- lightgbm  
- tabulate  

You can install all dependencies using:

```bash
pip install -r requirements.txt
```

## Contact
For collaboration inquiries, please contact:

Amey Chitnis

Email: amey.chitnis@tuhh.de