# 📊 Customer Churn Prediction with TensorFlow and ANN

This repository contains a Jupyter Notebook that builds and trains an Artificial Neural Network (ANN) to predict customer churn using the `Churn_Modelling.csv` dataset. The goal is to help banks identify customers who are likely to leave, allowing for better customer retention strategies.

---

## 📁 Dataset

The dataset `Churn_Modelling.csv` contains details about bank customers, such as:

- Row Number
- CustomerId
- Surname
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumberOfProducts
- HasCreditCard
- IsActiveMember
- Esitmated Salary
- Exited (target variable)

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas & NumPy** for data manipulation
- **Scikit-learn** for preprocessing and evaluation
- **TensorFlow/Keras** for building and training the ANN
- **Jupyter Notebook** as the development environment

---

## 🧠 Model Architecture

The model is a sequential Artificial Neural Network with:
- Input layer: Preprocessed customer features
- Two hidden layers: Each with 6 units and ReLU activation
- Output layer: 1 unit with Sigmoid activation for binary classification

Compiled with:
- Optimizer: `adam`
- Loss: `binary_crossentropy`
- Metric: `accuracy`

---

## ⚙️ How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/sudeepsrawat/Customer-Churn-Prediction-with-TensorFlow-and-ANN.git
    cd Customer-Churn-Prediction-with-TensorFlow-and-ANN
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Launch Jupyter Notebook:
    ```bash
    jupyter notebook Churn_Modelling_with_ANN.ipynb
    ```

4. Open the notebook and run the cells sequentially.

---

## ✅ Results

- Accuracy is computed using the test set.
- A confusion matrix is used to evaluate model performance.

---
