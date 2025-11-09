# 🏪 ML Project - Big Mart Sales Prediction  

## 🚀 Overview  
This **Machine Learning project** focuses on **Big Mart Sales Prediction** using the **XGBoost Regressor** algorithm. The model predicts product sales based on features such as **Item Weight, Item Fat Content, Item Visibility, Item Type, Item MRP, Outlet Identifier, Outlet Establishment Year, Outlet Size, Outlet Location Type, and Outlet Type**.  

Extensive **Exploratory Data Analysis (EDA)** was performed, including **weight, visibility, MRP, and sales distributions**, along with analysis of **outlet establishment year** and **fat content** trends.  

The model achieved an impressive **R² value of 0.87**, demonstrating strong predictive performance. This project showcases ML applications in **retail sales forecasting and inventory planning**.  

---

## 🔍 About the Project  
This project demonstrates how **machine learning regression algorithms** can be used for **business forecasting**.  
By analyzing product and outlet attributes, the system predicts the expected sales for different items across multiple retail outlets.  
The insights help businesses make data-driven decisions for inventory management and pricing strategies.  

---

## 🧠 Model Architecture  
The project employs the **XGBoost Regressor**, an advanced gradient boosting algorithm that combines multiple weak learners to deliver high predictive accuracy while minimizing overfitting.  

* **Algorithm:** XGBoost Regressor  
* **Problem Type:** Regression  
* **Evaluation Metrics:** R² Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)  

---

## 🧾 Dataset Description  
The dataset contains product-level and outlet-level details that influence sales:  

| Feature | Description |
|----------|-------------|
| **Item_Weight** | Weight of the product |
| **Item_Fat_Content** | Whether the product is low fat or regular |
| **Item_Visibility** | Visibility of the product in the store |
| **Item_Type** | Category of the product |
| **Item_MRP** | Maximum Retail Price of the product |
| **Outlet_Identifier** | Unique store ID |
| **Outlet_Establishment_Year** | Year when the outlet was established |
| **Outlet_Size** | Size of the outlet (Small / Medium / Large) |
| **Outlet_Location_Type** | City tier classification |
| **Outlet_Type** | Type of outlet (Grocery Store, Supermarket Type1/2/3) |
| **Item_Outlet_Sales** | Target variable — product sales at that store |

---

## ⚙️ Tech Stack & Libraries  

**Language:**  
* Python 🐍  

**Libraries:**  
* **NumPy** – Numerical computations  
* **Pandas** – Data manipulation and preprocessing  
* **Scikit-learn** – Model evaluation metrics  
* **XGBoost** – Regression modeling  
* **Matplotlib / Seaborn** – Visualization and EDA  

---

## 🚀 Features  
* Predicts **sales** based on item and outlet attributes  
* Performs **detailed EDA** with distribution and correlation analysis  
* Utilizes **XGBoost Regressor** for strong predictive accuracy  
* Achieves an **R² score of 0.87** on test data  
* Useful for **retail analytics**, **inventory planning**, and **business forecasting**  

---

## 📊 Results  
The **XGBoost Regressor** achieved an **R² value of 0.87**, indicating a strong model fit for predicting Big Mart product sales.  
The model helps understand how factors like **MRP**, **outlet type**, and **visibility** influence sales outcomes.  

---

## 📁 Repository Structure  

```
📦 ML-Projects-Mart-Sales-Prediction
│
├── BigMart_Sales_Prediction.ipynb # Complete model implementation
├── BigMartSales.csv # Dataset used for training and testing
├── requirements.txt # Required dependencies
└── README.md # Project documentation

```
---

## 🧪 How to Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/ms00000ms0000/ML-Projects-Mart-Sales-Prediction.git
   cd ML-Projects-Mart-Sales-Prediction
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook BigMart_Sales_Prediction.ipynb
   ```

4. **Execute all cells to train, test, and evaluate the model performance.**

---

## 📈 Future Improvements

* Integrate hyperparameter tuning using GridSearchCV for optimization.

* Add a Streamlit dashboard for real-time sales prediction.

* Experiment with Neural Networks or LightGBM for comparative analysis.

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava
