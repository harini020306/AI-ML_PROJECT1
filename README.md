# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts the selling price of a house based on its features such as area, number of bedrooms, bathrooms, and age of the house. The model is built using Machine Learning algorithms and deployed with Streamlit to provide real-time predictions.

---

## 🎯 Problem Statement

House prices depend on various factors like location, size, number of rooms, and age of the property. Predicting house prices manually is difficult and time-consuming. This project uses Machine Learning techniques to estimate house prices accurately based on historical housing data.

---

## 🚀 Objectives

- Predict house prices using Machine Learning.
- Perform data preprocessing and exploratory data analysis (EDA).
- Train and evaluate different regression models.
- Save the trained model using Pickle.
- Deploy the model using Streamlit.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
- Pickle

---

## 📂 Dataset

The dataset contains information about houses such as:

- Area
- Number of Bedrooms
- Number of Bathrooms
- Age of the House
- Price (Target Variable)

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Data Inspection
- Missing Value Handling
- Duplicate Removal
- Statistical Summary
- Correlation Matrix
- Heatmap
- Histogram
- Box Plot
- Feature Distribution

---

## ⚙️ Machine Learning Workflow

1. Load Dataset
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Selection
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Save Model
9. Streamlit Deployment

---

## 🤖 Machine Learning Algorithm

**Linear Regression**

The Linear Regression algorithm is used to predict house prices based on input features.

---

## 📈 Evaluation Metrics

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📁 Project Structure

```
House-Price-Prediction/
│
├── app.py
├── house_price_prediction.ipynb
├── house_model.pkl
├── scaler.pkl
├── requirements.txt
├── README.md
├── data.csv
└── images/
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/House-Price-Prediction.git
```

Move into the project directory

```bash
cd House-Price-Prediction
```

Install required packages

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Streamlit App

```bash
streamlit run app.py
```

---

## 💻 Sample Input

| Feature | Example |
|----------|---------|
| Area | 1800 |
| Bedrooms | 3 |
| Bathrooms | 2 |
| Age | 10 |

---

## 📌 Sample Output

```
Predicted House Price:
₹ 58,75,000
```

---

## 📷 Application Screenshot

Add screenshots of your Streamlit application here.

Example:

```
images/homepage.png
images/prediction.png
```

---

## 📌 Future Enhancements

- Improve prediction accuracy using advanced algorithms.
- Add location-based prediction.
- Deploy the application on Streamlit Cloud.
- Integrate with real estate APIs.
- Build a responsive web interface.

---

## 👩‍💻 Author

**Harini**

B.E. Electronics and Communication Engineering

Machine Learning Enthusiast

---

## ⭐ Conclusion

This project demonstrates the complete Machine Learning workflow from data preprocessing and model training to deployment using Streamlit. It provides an easy-to-use interface for predicting house prices based on user inputs.

---

## 📜 License

This project is developed for educational purposes.
