# Deep Learning and Explainable AI for Diabetes Risk Prediction

## MSc Computer Science Individual Research Project

This repository contains the final coding artefact for the research project **Deep Learning and Explainable AI for Diabetes Risk Prediction**.

The project develops and evaluates a three-class diabetes-status classification prototype using an African diabetes dataset. The classes are:

- Diabetic
- Prediabetes
- Normal

The artefact combines data preprocessing, supervised machine learning, artificial neural networks (ANN), deep neural networks (DNN), XGBoost, and explainable AI using SHAP and LIME.

> **Important:** This is a research/decision-support prototype and is **not a diagnostic system** and must not be used to make clinical or treatment decisions.

## Main technologies

- Python
- pandas
- NumPy
- scikit-learn
- imbalanced-learn / SMOTENC
- TensorFlow / Keras
- XGBoost
- SHAP
- LIME
- Matplotlib
- Seaborn
- Joblib

## Notebook

The main artefact is:

`Anoop_Code_Final_Code.ipynb`

The notebook contains the project workflow, including data preparation, exploratory analysis, model development, evaluation and explainability.

## Dataset

The project uses the African diabetes dataset described in the accompanying dissertation/report.

The patient-level dataset is **not included in this repository**. This repository therefore avoids unnecessarily publishing patient-level data. The dataset should be obtained from its permitted original source and placed locally as `Dataset.csv` before running the notebook.

## Running the project

### 1. Install Python

Python 3.10+ is recommended.

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add the dataset

Place the permitted dataset file in the project directory as:

```text
Dataset.csv
```

### 4. Run the notebook

Open:

```text
Anoop_Code_Final_Code.ipynb
```

using Jupyter Notebook, JupyterLab, or a compatible notebook environment.

## Research artefact

The project evaluates ANN, DNN and XGBoost models and uses SHAP and LIME to investigate model behaviour and influential features.

The dissertation reports that XGBoost was the strongest model in the experiment for this moderate-sized tabular dataset, while also discussing the value and limitations of deep learning and explainability.

## Responsible use

The system is intended as research software / decision support. Predictions should not be interpreted as medical diagnoses or treatment recommendations.

Healthcare data can contain privacy, bias, representativeness, leakage and governance risks. The accompanying dissertation discusses these limitations and the need for appropriate validation and human oversight.

## Repository contents

```text
deep-learning-diabetes-risk-prediction/
├── Anoop_Code_Final_Code.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Academic submission

This repository contains the coding artefact associated with the final MSc research project submission. The repository should remain unchanged after final submission in accordance with the project submission instructions.
