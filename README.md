# Marine Microplastic Concentration Prediction  
### *A Machine Learning Model Comparison Study*

**Author:** Abhinav Tyagi  
**MSc Business Analytics, Dublin Business School**

This repository contains the full implementation, analysis, and documentation for my MSc dissertation project titled:

**Predicting Marine Microplastic Concentration Using Environmental, Spatial, and Anthropogenic Features**

---

## 🚀 Project Summary

Microplastic pollution is a growing global concern. This project develops a machine‑learning‑based framework to predict microplastic concentration using:

- Environmental variables (SST, salinity, ocean currents)
- Spatial variables (latitude, longitude, region)
- Anthropogenic variables (population density)
- Sampling methodology (mesh size, method type)

Five supervised learning models were evaluated:

- Random Forest  
- Gradient Boosting  
- Support Vector Regression  
- Multilayer Perceptron  
- **XGBoost (best performer, R² ≈ 0.84)**

---

## 📁 Repository Structure

```
docs/                     # Dissertation & presentation
src/                      # Python scripts
notebooks/                # Jupyter notebooks
results/                  # Visualisations & outputs
data/                     # Sample dataset + metadata
requirements.txt
README.md
```

---

## 🔧 Installation

```
pip install -r requirements.txt
```

---

## ▶️ How to Run the Project

### 1. Preprocess data
```
python src/preprocessing.py
```

### 2. Train models
```
python src/model_training.py
```

### 3. Evaluate performance
```
python src/evaluation.py
```

---

## 📊 Key Results

- **XGBoost achieved the highest predictive accuracy (R² ≈ 0.84)**  
- Most influential predictors:
  - Geographic region  
  - Ocean current speed  
  - Sea surface temperature  
  - Seasonal variability  
  - Sampling methodology  

---

## 🧭 Future Work

- Integrate hydrodynamic drift models  
- Use satellite‑derived ocean circulation  
- Apply Lagrangian particle tracking  
- Explore deep learning architectures  
- Develop a real‑time prediction dashboard  

---

## 📄 Documentation

Full dissertation and presentation slides are available in the **docs/** folder.

---

## 📜 License

MIT License
