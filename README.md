# House Price Prediction Web App

A machine learning web application built with Flask that predicts house prices based on property features.
The application takes user inputs from a web form, sends them to a trained machine learning model, and returns the predicted house price.

This project demonstrates how to integrate a trained machine learning model with a web interface using Python and Flask.

---
Deployment: https://house-price-prediction-ko64.onrender.com/  
---
## Features

* Predict house prices using a trained machine learning model
* Simple web interface for user input
* Flask backend for handling prediction requests
* Uses Pandas for data preprocessing
* Uses Joblib to load the trained model

---

## Tech Stack

* Python
* Flask
* Pandas
* Scikit-learn
* Joblib
* HTML (templates)

---

## Project Structure

```
house-price-prediction/
│
├── app.py
├── house_price_model.pkl
├── requirements.txt
│
├── templates/
│   ├── index.html
│   └── result.html
│
└── static/
```

---

## Model Inputs

The model predicts house prices based on the following features:

| Feature       | Description                            |
| ------------- | -------------------------------------- |
| Overall Qual  | Overall material and finish quality    |
| Gr Liv Area   | Above ground living area (square feet) |
| Garage Cars   | Garage capacity in number of cars      |
| Total Bsmt SF | Total basement area (square feet)      |
| Full Bath     | Number of full bathrooms               |
| Year Built    | Year the house was built               |

---

## How It Works

1. The user enters house details in the web form.
2. Flask receives the form data through a POST request.
3. The input values are converted into a Pandas DataFrame.
4. The trained machine learning model predicts the house price.
5. The predicted value is displayed on the results page.

---

## Running the Project

### 1. Clone the repository

```
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the Flask application

```
python app.py
```

### 4. Open the application in your browser

```
http://127.0.0.1:5000
```

---

## Requirements

Example `requirements.txt`:

```
Flask
pandas
scikit-learn
joblib
```

---

## License

This project is licensed under the MIT License.

---

## Author

Koushal
Computer Science Student | Python Developer | AI and Automation Enthusiast
