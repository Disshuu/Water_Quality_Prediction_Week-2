# Water Quality Prediction - RMS

This project aims to predict multiple water quality parameters using machine learning techniques, specifically `MultiOutputRegressor` wrapped around a `RandomForestRegressor`. It was developed as part of a one-month **AICTE Virtual Internship sponsored by Shell** in **June 2025**.

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

The model predicts multiple water quality parameters such as:

- NH4
- BOD5 (BSK5)
- Colloids
- O2, NO3, NO2, SO4, PO4 and 
- CL

---

## Model Performance

The model was evaluated using:

- **R² Score**
- **Mean Squared Error (MSE)**

Performance was acceptable across all parameters

---

## Model link: 

https://drive.google.com/file/d/1thH9BZbL5Gv0vYnkR6q1u1wcV6O5pU6_/view?usp=sharing

---
## Internship Details

- **Internship Type**: AICTE Virtual Internship - Edunet Foundation
- **Sponsor**: Shell  
- **Duration**: June 2025 (1 month)  
- **Focus Area**: Machine Learning in Environmental Monitoring  

---
##  Author

**Divya Ramnani**  
B.Tech – Data Science, IPS Academy  
Aspiring AI/ML engineer passionate about building solutions for sustainability and public welfare.

---

##  Note

This project was implemented using Google Colab to enable easy experimentation, interactive model training, and streamlined deployment.
