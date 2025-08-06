# AgroSmart 🌾
A machine learning project focused on analyzing and predicting crop performance based on agricultural variables like rainfall, irrigation, and fertilizer use. Developed as part of the **Samsung Innovation Campus 2024**.

## 📌 Overview

AgroSmart applies multiple machine learning techniques to optimize agricultural production:
- **Multiple Linear Regression** to predict yield per hectare based on rainfall, fertilizer, and irrigation.
- **Random Forest** classifier to predict binary use of irrigation/fertilizer.
- **K-Means Clustering** to segment similar crop conditions based on soil, climate, and yield.

## 🚜 Dataset

The dataset includes:
- Rainfall (mm)
- Fertilizer used
- Irrigation status
- Soil type
- Crop type
- Region
- Temperature
- Days to harvest
- Yield (tons per hectare)

## 📊 ML Techniques

### 1. Regression
- Used to model the relation between rainfall, fertilizer, and irrigation with yield.
- Optimization via gradient descent.
- Evaluated with MSE and K-Fold Cross Validation.

### 2. Classification
- Random Forest classifier to determine:
  - Whether irrigation was used.
  - Whether fertilizer was applied.
- Accuracy: ~81% in all test settings.

### 3. Clustering
- K-Means algorithm with PCA for dimensionality reduction.
- Optimal `k` value determined via Elbow method.
- Segmentation based on rainfall and yield.

## 📷 Visualizations
Some of the included visualizations:
- Heatmaps for feature correlation
- MSE evolution plot
- 3D regression surface
- Clustering diagrams and PCA projection

## 🛠️ Technologies
- Python
- pandas, numpy, scikit-learn
- matplotlib, seaborn
- PCA, ColumnTransformer
- Google Colab (for training)

## 🧠 Authors
This project was developed as a team effort as part of the Samsung Innovation Campus 2024.  
Team members:
- Jesús Antonio Torres Contreras
- Joshua David Salcedo Monroy
- Luis Ángel Lozano Reyes
- Gregorio Salazar Solís

## 📚 License
This project is for academic and educational purposes.

