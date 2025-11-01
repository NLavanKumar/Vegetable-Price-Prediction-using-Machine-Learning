# 🥦 Vegetable Price Prediction using Machine Learning

This project aims to predict the prices of vegetables based on various market and seasonal factors using different machine learning algorithms. The goal is to help farmers, vendors, and market analysts make informed decisions by forecasting price trends.

---

## 🚀 Project Overview

Vegetable prices often fluctuate due to factors such as demand, season, and supply chain variations. To tackle this, a machine learning model is trained to predict vegetable prices based on historical data. The project compares multiple regression algorithms — **Linear Regression**, **Random Forest**, **K-Nearest Neighbors (KNN)**, and **Support Vector Machine (SVM)** — to find the most accurate model.

---

## 🧠 Algorithms Used

- **Linear Regression** – For simple and interpretable prediction modeling  
- **Random Forest Regressor** – For handling nonlinear relationships and feature importance  
- **K-Nearest Neighbors (KNN)** – For local pattern-based prediction  
- **Support Vector Machine (SVM)** – For robust prediction with kernel-based learning  

---

## 🧾 Dataset

The dataset contains:
- Vegetable name  
- Market date  
- Quantity sold  
- Demand/Supply indicators  
- Historical price data  

*(If using a custom or open dataset, mention the source here. Example: "Data collected from government agricultural price portals or Kaggle datasets.")*

---

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Vegetable-Price-Prediction-Using-ML.git

2. Navigate to the project folder:
```bash
  cd Vegetable-Price-Prediction-Using-ML
```
3. Install dependencies:
```
pip install -r requirements.txt

```
4. Open the Jupyter notebook:
```
jupyter notebook Vegetable_Price_Prediction.ipynb
```

📊 Model Evaluation

Each model was evaluated using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

The model with the lowest error and highest R² value is chosen as the best-performing algorithm.

🏆 Results
Algorithm	        R² Score	MAE	   MSE
Linear Regression	0.82	    4.5	   26.3
Random Forest	    0.91	    3.2	   15.7
KNN	              0.86	    4.1	   22.9
SVM	              0.88	    3.8	   19.4

(You can replace these with your actual evaluation results.)

📈 Future Enhancements

Integrate real-time data fetching from government or market APIs

Develop a Streamlit-based web dashboard for live predictions

Add feature engineering and hyperparameter tuning for improved accuracy

🧑‍💻 Technologies Used

Python

NumPy, Pandas

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook

🤝 Contributors

Your Name – Machine Learning Developer

🪪 License

This project is licensed under the MIT License
.

🌟 Acknowledgment

Special thanks to open-source contributors and datasets that made this project possible.


---


