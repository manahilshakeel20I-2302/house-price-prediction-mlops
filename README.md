# House Price Prediction API (MLOps Pipeline)

This project demonstrates an end-to-end machine learning workflow, including model training, testing, and deployment using a Flask API.

---

## Overview

The pipeline predicts house prices using a structured dataset and exposes the trained model through an API.

Key features:

* Data preprocessing and feature handling
* Model training and evaluation
* REST API built with Flask
* Unit testing using Python's `unittest`

---

## Tech Stack

* Python
* pandas, scikit-learn
* Flask
* unittest

---

## Workflow

1. Preprocess housing dataset
2. Train regression model
3. Save trained model
4. Serve predictions via Flask API
5. Validate components with unit tests

---

## API Endpoint

**POST /predict**

Accepts input features as JSON and returns the predicted house price.

---

## Testing

Unit tests are implemented using `unittest` to ensure:

* Data processing works correctly
* Model prediction runs without errors
* API endpoints respond as expected

---

## What This Project Demonstrates

* End-to-end ML pipeline development
* Model deployment using Flask
* Basic testing practices in ML systems
* Understanding of MLOps fundamentals

---

## Dataset

* House Prices dataset (publicly available)

---

## 📄 License

MIT


PROJECT BY: Manahil Shakeel 20I-2302 and Fatima Fateen 20I-2328
