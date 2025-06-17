# Water Quality Prediction 

🌍 Problem Statement
Water pollution is a growing concern globally. Monitoring water quality in real-time and predicting pollutant levels can significantly help authorities prevent ecological damage and protect public health.

This project aims to develop a machine learning model that can predict multiple water quality parameters simultaneously, based on historical water quality datasets.

---

## Overview

Access to clean water is a critical global concern. Accurate prediction of various water quality metrics can help in early detection of pollution and ensure timely intervention.

In this project, we:

- Collected and preprocessed real-world water quality datasets
- Used supervised machine learning for multi-target regression
- Built a pipeline using `MultiOutputRegressor` with `RandomForestRegressor`
- Evaluated the model using appropriate regression metrics

---

## Technologies Used

- **Python 3.12**
- **Pandas, NumPy** – Data handling
- **Scikit-learn** – Machine learning model and evaluation
- **Matplotlib, Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive experimentation

---

## Predicted Water Quality Parameters

📂 Dataset Description
The dataset includes readings of various physicochemical properties from water bodies. Some of the key features include:

Temperature

pH

Turbidity

Conductivity

Dissolved Oxygen (DO)

And more...

The target variables (multi-output regression) are:

NH₄ (Ammonium)

BOD₅ (Biological Oxygen Demand)

Colloids

O₂ (Oxygen)

NO₃ (Nitrate)

NO₂ (Nitrite)

SO₄ (Sulfate)

PO₄ (Phosphate)

Cl (Chloride)
---

## Model Performance

The model was evaluated using:

- **R² Score**
- **Mean Squared Error (MSE)**

Performance was acceptable across all parameters

---

## Internship Details

- **Internship Type**: AICTE Virtual Internship - Edunet Foundation
- **Sponsor**: Shell  
- **Duration**: June 2025 (1 month)  
- **Focus Area**: Machine Learning in Environmental Monitoring  

---
