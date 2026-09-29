# Brain Stroke Detection Using Hybrid Machine Learning

## Overview

This project is a machine learning-based system designed to predict the risk of brain stroke using patient health information. It uses a **hybrid stacking ensemble model** combining Random Forest, Gradient Boosting, and Logistic Regression to improve prediction performance.

The project also uses **SMOTE** to handle class imbalance and **SHAP** to provide explainable insights into the factors influencing the model's predictions.

## Features

* Hybrid stacking ensemble machine learning model
* Brain stroke risk prediction using patient health parameters
* Random Forest, Gradient Boosting, and Logistic Regression
* SMOTE for handling class imbalance
* Feature engineering for improved prediction
* Explainable AI using SHAP
* Personalized stroke risk prediction

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* SHAP
* Matplotlib
* Seaborn
* Jupyter Notebook

## Machine Learning Models

The project uses a stacking ensemble approach that combines:

* **Random Forest**
* **Gradient Boosting**
* **Logistic Regression**

SMOTE is applied during data preprocessing to address the class imbalance in the stroke dataset.

## Model Performance

| **Metric** | **Score** |
| ---------- | --------- |
| Accuracy   | 93–95%    |
| Precision  | 90–93%    |
| Recall     | 92–95%    |
| ROC-AUC    | 0.95–0.97 |

## How to Run

1. Clone the repository.

2. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

3. Place the `Stroke.csv` dataset in the project directory.

4. Open the Jupyter Notebook:

```text
brain_stroke_detection.ipynb
```

5. Run the notebook cells to preprocess the data, train the model, evaluate its performance, and generate stroke-risk predictions.


## Future Improvements

* Develop a web-based application
* Integrate real-time health monitoring
* Explore deep learning models
* Deploy the model using cloud services
* Improve model interpretability and prediction capabilities
