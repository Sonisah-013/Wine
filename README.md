# Wine Prediction

Machine learning project to **predict wine types** (Barolo, Grignolino, Barbera) using **chemical features**. This project demonstrates data exploration, modeling, evaluation, and visualization in Python.

---

## Project Overview

- **Goal:** Predict wine type from chemical features  
- **Task Type:** Supervised classification problem  
- **Dataset:** 178 samples, 13 chemical features, 3 wine types (Barolo, Grignolino, Barbera)  
- **Approach:** Train multiple ML models and select the best performing model  
- **Objective:** Achieve accurate classification of wine types  
- **Outcome:** High-performing models with visual evaluation metrics

---

## Dataset

The dataset contains **13 chemical features** measured for 178 wine samples:

| Feature | Description |
|---------|-------------|
| Alcohol | % of alcohol |
| Malic Acid | g/l |
| Ash | g/l |
| Alcalinity of Ash | meq/l |
| Magnesium | mg/l |
| Total Phenols | mg/l |
| Flavanoids | mg/l |
| Nonflavanoid Phenols | mg/l |
| Proanthocyanins | mg/l |
| Color Intensity | unitless |
| Hue | unitless |
| OD280/OD315 of Diluted Wines | unitless |
| Proline | mg/l |

> **Target Variable:** Wine Type (Barolo, Grignolino, Barbera)

---

## Exploratory Data Analysis (EDA) & Visualization

- **Feature Distribution Plots:** Understand spread of chemical features across wine types  
- **Correlation Heatmap:** Identify relationships between features  
- **Pair Plots:** Visualize feature interactions  
- **Class Distribution:** Check balance among wine types  

*Example Diagram:*

```text
Chemical Features (13)
          ↓
   Machine Learning Models
(Logistic Regression, Random Forest, SVM)
          ↓
Predicted Wine Type (Barolo, Grignolino, Barbera)
