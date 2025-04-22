# Crop Yield Prediction 🚜🌾

Predict crop yield categories (Low, Medium, High) using machine learning! This project leverages **Random Forest Classifier** for classification and **KMeans clustering** to analyze patterns in agricultural data.

---

## 🌱 Project Overview

We use **soil quality**, **rainfall**, and **seed type** data to predict crop yield categories. This helps farmers optimize their resources and improve crop management.

- **Supervised Learning**: Predicting yield category using Random Forest.
- **Unsupervised Learning**: Segmenting the data using KMeans clustering.

---

## 📊 Dataset

The dataset contains **101 samples** with the following features:
- `soil_quality` (Numerical)
- `rainfall` (Numerical)
- `seed_type` (Categorical: A, B, C)
- `yield_category` (Target: Low, Medium, High)

---

## 🚀 Quick Start

1. **Clone the repo**:
   ```bash
   git clone https://github.com/your-username/Crop-Yield-Prediction.git
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebook (notebook.ipynb) to train the model and visualize the results.

🎯 Results
Accuracy: 85% (Random Forest Classifier).

Visualizations: Confusion matrix, clustering patterns.

⚙️ Technologies
Python 3

Libraries: pandas, numpy, matplotlib, scikit-learn

Jupyter Notebook (or Google Colab)
