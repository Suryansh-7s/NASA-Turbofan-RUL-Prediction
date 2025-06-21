# 🚀 Predictive Maintenance of Turbofan Engines using NASA C-MAPSS Dataset

This project applies classical ML and deep learning models to predict the **Remaining Useful Life (RUL)** of jet engines using the **NASA C-MAPSS dataset**. The objective is to enable predictive maintenance and minimize unplanned downtime.

---

## 📊 Dataset Summary

| Dataset | Operating Conditions | Fault Modes | Train / Test Engines |
|---------|----------------------|-------------|-----------------------|
| FD001   | 1                    | 1           | 100 / 100             |
| FD002   | 6                    | 1           | 260 / 259             |
| FD003   | 1                    | 2           | 100 / 100             |
| FD004   | 6                    | 2           | 248 / 249             |

Each record includes engine ID, cycle, 3 operating settings, 21 sensor readings, and RUL labels (for test set).

---

## 🧠 Models Implemented

- Linear Regression  
- Support Vector Regression (SVR)  
- Random Forest Regressor  
- Multilayer Perceptron (MLP)  
- Long Short-Term Memory (LSTM)

---

## 📈 Evaluation Metrics

- RMSE (Root Mean Squared Error)  
- R² Score  

---

## 📌 Sample Results

| Model  | FD001 | FD002 | FD003 | FD004 |
|--------|--------|--------|--------|--------|
| LR     | 36.2  | 41.7   | 39.5   | 42.1   |
| SVR    | 24.4  | 29.8   | 26.7   | 27.4   |
| RF     | 20.1  | 22.5   | 18.3   | 20.8   |
| MLP    | 19.3  | 21.2   | 17.6   | 19.9   |
| LSTM   | 16.2  | 18.6   | 16.8   | 16.2   |

---

## 🔭 Future Work

- Transformer-based sequence models  
- Real-time dashboards via Streamlit  
- GPU-accelerated hyperparameter tuning  
- Explainability (SHAP, LIME)  
- Transfer learning for generalization

---

## 📚 References

- NASA C-MAPSS Dataset – [Link](https://www.nasa.gov/data/CMAPSS)  
- Saxena et al. (2008) – *Damage Propagation Modeling for Aircraft Engines*  
- Heimes (2008) – *Recurrent Neural Networks for RUL Estimation*  
- Smola & Schölkopf (2004) – *Support Vector Regression Tutorial*  
- Gebraeel & Pan (2008) – *Degradation Models in Time-Varying Environments*

---

> ⚠️ Note: This project was submitted under a team as per university rules, but all development, modeling, experimentation, and documentation were solely performed by **Suryansh Sharma**.

---

## 🔐 License & Usage

This repository is for **educational demonstration only**.  
No part of the code or data may be reused or modified without permission.

© 2025 Suryansh Sharma. All rights reserved.

---

## 📬 Contact

📧 Email: sharmasuryansh2004@gmail.com  
🔗 LinkedIn: [Suryansh Sharma](https://www.linkedin.com/in/suryansh-sharmaseven/)
