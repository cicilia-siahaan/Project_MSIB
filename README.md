# Tutorial Modelling Data Titanic

Tutorial ini akan mengolah data titanic menjadi data yang siap untuk dilakukan pemodelan

## Prerequisites

1. Download data [here](https://www.kaggle.com/datasets/vinicius150987/titanic3?select=titanic3.xls)
2. Instalansi dengan `pip install requirements.txt`

## Getting Started

- Dataset Splitting
- Training
- Model Validation

### Dataset Splitting

split data into training, validation and test sets
```code
X_train, y_train, X_test, y_test = data_splitting()
X_train.shape, y_train.shape
```

## References

1. Di scikit-learn documentation