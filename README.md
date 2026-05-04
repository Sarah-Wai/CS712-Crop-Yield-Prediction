# Crop Yield Prediction Using Linear Regression and Random Forest

## Overview
This project predicts crop yield using machine learning techniques, specifically Multiple Linear Regression and Random Forest. The workflow includes data preprocessing, model training, and evaluation using real-world agricultural datasets.

---

## Repository Structure

```
CS712-Crop-Yield-Prediction/
├── data_preprocessing_crop_yield-checkpoint.ipynb
├── apply_model_crop_yield-checkpoint.ipynb
├── data/
│   ├── LandCover_raw.xlsx
│   ├── pesticides_raw.xlsx
│   ├── rainfall_raw.xlsx
│   ├── temp_raw.xlsx
│   └── yield_raw.xlsx
└── README.md
```

---

## Getting Started

### 1. Clone the Repository

```
git clone https://github.com/Sarah-Wai/CS712-Crop-Yield-Prediction.git
cd CS712-Crop-Yield-Prediction
```

---

### 2. Install Requirements

Ensure Python is installed, then run:

```
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

### 3. Run the Notebooks

#### Step 1: Data Preprocessing

Run:
```
data_preprocessing_crop_yield-checkpoint.ipynb
```

This will:
- Clean and merge datasets
- Generate the processed dataset:
```
yield_df.csv
```

---

#### Step 2: Apply Models

Run:
```
apply_model_crop_yield-checkpoint.ipynb
```

This notebook:
- Trains Linear Regression and Random Forest models
- Evaluates model performance

---

## Output

- Evaluation metrics:
  - MAE (Mean Absolute Error)
  - MSE (Mean Squared Error)
  - RMSE (Root Mean Squared Error)
  - R² Score
- Visualization of predicted vs actual yields
- Feature importance analysis (Random Forest)

---

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Authors

Wai Phu Paing  
Jesmin Akter  

CS712 Group Project  
University of Regina
 
🔗 CS712 Group Project, University of Regina
