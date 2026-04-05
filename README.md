# Predicting Heart Disease Using Machine Learning

This project uses Python-based machine learning and data science libraries to build a model capable of predicting whether or not a patient has heart disease based on their clinical attributes.

## Problem Definition

> Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## Approach

1. Problem Definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## Dataset

The dataset used is `heart-disease.csv`, containing anonymized patient medical records with features such as age, sex, chest pain type, blood pressure, cholesterol, and more.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/uttkarshyadavv/Heart-disease-prediction-ml.git
   cd Heart-disease-prediction-ml

   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook heart-disease.ipynb
   ```

## Results

Three models were evaluated and compared:

| Model | Accuracy |
|---|---|
| Logistic Regression | 88.52% |
| Random Forest | 83.61% |
| KNN | 68.85% |

**Best Model: Logistic Regression** — further tuned using GridSearchCV (5-fold, 150 fits), achieving best hyperparameters: `C = 0.2043`, `solver = liblinear`.

## License

This project is licensed under the terms of the LICENSE file included in this repository.
