**Machine Learning Stock Predictor**
<img width="523" alt="Screenshot 2024-10-14 233131" src="https://github.com/user-attachments/assets/c2b9c237-c5a3-4ff1-a096-e1813a986239">

**StockTrendPredictor**
StockTrendPredictor is a machine learning-based project that predicts short-term stock market trends (uptrends and downtrends) using various algorithms, including Support Vector Machines (SVM), Logistic Regression, and a Voting Classifier. The project combines historical stock data and technical indicators to forecast market movements and enhance trading strategies.

**Features**
Predicts stock market trends (up or down) based on historical stock data.
Implements multiple machine learning models:
Support Vector Machines (SVM)
Logistic Regression
Decision Tree
Voting Classifier (combines multiple models for better accuracy)
Uses financial technical indicators like:
Open-Close and High-Low price differences
Simple Moving Average (SMA)
Exponential Moving Average (EMA)
Evaluates models using metrics such as AUC (Area Under the ROC Curve), confusion matrix, and classification report.
Achieves high accuracy in predicting stock movements using ensemble learning techniques.

**Technologies Used**
**Python:** The core programming language used.
**scikit-learn:** For building and evaluating machine learning models.
**Pandas:** For data manipulation and analysis.
**NumPy:** For numerical computations.
**Matplotlib:** For plotting data and visualizations.

**How It Works**
Data Preprocessing: Stock data (open, high, low, close prices, etc.) is processed and relevant features (such as SMA, EMA, price differences) are engineered.
Model Training: The dataset is split into training and testing sets. Various models like SVM, Logistic Regression, and Decision Trees are trained on the data.
Voting Classifier: A voting classifier combines the predictions from SVM, Logistic Regression, and Decision Tree to provide more robust and accurate predictions.
Model Evaluation: The models are evaluated using AUC, confusion matrix, precision, recall, and F1-scores to assess their performance.

**Getting Started**
**Clone the repository:**git remote add origin https://github.com/Cyprians-Mwanza/StockTrendPredictor.git
**Install dependencies:**
numpy
pandas
scikit-learn
matplotlib
