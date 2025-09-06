# Deep Learning Data Task

This repository contains three exercises focused on data preprocessing and machine learning fundamentals.

## Exercises

### Exercise 1: Classification
- **File**: `exercise1.ipynb`
- **Description**: Compare linear and non-linear classification using logistic regression and MLP
- **Dataset**: Synthetic 2D data with 4 classes
- **Key concepts**: Decision boundaries, linear vs non-linear models

### Exercise 2: Dimensionality Reduction
- **File**: `exercise2.ipynb`
- **Description**: Apply PCA to reduce 5D data to 2D and visualize results
- **Dataset**: Synthetic 5D multivariate normal data
- **Key concepts**: Principal Component Analysis, explained variance

### Exercise 3: Data Preprocessing
- **File**: `exercise3.ipynb`
- **Description**: Preprocess spaceship passenger data for machine learning
- **Dataset**: Spaceship Titanic passenger data (`data/train.csv`)
- **Key concepts**: Missing value imputation, feature scaling, categorical encoding

## Setup

1. Create a virtual environment:
```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run Jupyter notebooks:
```bash
jupyter notebook
```

## Data

- `data/train.csv`: Spaceship passenger data for Exercise 3
- `data/test.csv`: Test data (if needed)
- `images/`: Generated plots and visualizations

## Requirements

- Python 3.10+
- Jupyter Notebook
- scikit-learn
- pandas
- numpy
- matplotlib