# Disease Prediction System Using Machine Learning

This project is a web-based application that predicts the likelihood of three diseases: **Diabetes**, **Heart Disease**, and **Parkinson's Disease**, using pre-trained machine learning models. It provides a simple, user-friendly interface for entering health details and receiving predictions.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Technologies Used](#technologies-used)
- [Disclaimer](#disclaimer)

---

## Overview

The Disease Prediction System aims to provide a preliminary risk assessment for three major diseases. This tool is designed for educational purposes, enabling users to understand potential health risks based on their input data.

---

## Features

1. **Diabetes Prediction**
   - Predicts diabetes risk based on parameters like glucose level, BMI, insulin, and age.

2. **Heart Disease Prediction**
   - Evaluates the risk of heart disease using inputs such as cholesterol level, blood pressure, and other medical details.

3. **Parkinson's Disease Prediction**
   - Identifies the likelihood of Parkinson's disease based on voice and medical attributes like jitter and shimmer.

---

## Installation

Follow these steps to set up and run the project:

1. Clone this repository or download the source code.
2. Install Python 3.x if not already installed.
3. Install the required Python packages:
   ```bash
   pip install streamlit
   pip install streamlit-option-menu

Usage
Run the application:
bash

   streamlit run app.py
Open the app in your web browser using the link provided by Streamlit.
Navigate between the prediction pages for Diabetes, Heart Disease, or Parkinson's Disease using the sidebar menu.
Input your health details and click the "Test Result" button to receive a prediction.
How It Works
The app is built using Streamlit, a Python framework for creating interactive web applications.
Pre-trained machine learning models (stored as .sav files) are used to make predictions.
The user inputs are processed and fed into the respective model to generate a prediction.
Results are displayed directly on the app page.
Technologies Used
Programming Language: Python 3.x
Framework: Streamlit
Libraries:
streamlit
streamlit-option-menu
pickle (for loading machine learning models)
Disclaimer
This application is intended for informational and educational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of a qualified healthcare provider with any questions you may have regarding a medical condition.
