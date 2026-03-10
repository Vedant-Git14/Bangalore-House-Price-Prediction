# 🏠 Bangalore House Price Prediction | ML Project

A Machine Learning web application that predicts house prices in Bangalore based on user inputs such as location, square footage, number of bedrooms (BHK), and bathrooms.
The application uses a trained regression model and a Flask backend to provide real-time price predictions through a simple and interactive web interface.

---

## 🚀 Project Overview

This project demonstrates the practical implementation of a Machine Learning model in a web application.
Users can enter property details and instantly get an estimated house price.

The project integrates:

* **Machine Learning Model**
* **Flask Web Framework**
* **Interactive Frontend**
* **Real-time Prediction**

---

## 🧠 Machine Learning Model

The prediction model is trained on Bangalore housing data using regression techniques.

Features used for prediction:

* Location
* Square Feet Area
* Number of Bedrooms (BHK)
* Number of Bathrooms

The trained model is stored using **Pickle** and loaded in the Flask backend for real-time predictions.

---

## 🖥️ Tech Stack

**Frontend**

* HTML
* CSS
* Bootstrap

**Backend**

* Python
* Flask

**Machine Learning**

* NumPy
* Scikit-Learn
* Pickle

---

## 📂 Project Structure

```
BHPP
│
├── app.py
├── banglore_home_prices_model.pickle
├── columns.json
│
├── templates
│   ├── index.html
│   └── predict.html
│
├── static
│   ├── style.css
│   └── favicon.ico
```

---

## ⚙️ How to Run the Project

1. Clone the repository

```
git clone https://github.com/Vedant-Git14/Bangalore-House-Price-Prediction.git
```

2. Navigate to the project folder

```
cd Bangalore-House-Price-Prediction
```

3. Install dependencies

```
pip install flask numpy scikit-learn
```

4. Run the Flask application

```
python app.py
```

5. Open in browser

```
http://127.0.0.1:5000
```

---

## 🎯 Features

* Predict house prices instantly
* Clean and responsive user interface
* Location-based price prediction
* Real-time ML model integration
* Interactive web form for user inputs

---

## 📌 Future Improvements

* Deploy the project online
* Add data visualization
* Improve model accuracy
* Add more property features

---

## 👨‍💻 Author

**Vedant Yadav**

GitHub: https://github.com/Vedant-Git14

---

⭐ If you like this project, consider giving it a star on GitHub!
