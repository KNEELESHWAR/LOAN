# Loan Approval Prediction

This project is a **Loan Approval Prediction** web application built using **Flask**. It allows users to input details like gender, marital status, education, income, etc., and predict the approval of a loan using different machine learning models (SVC, Logistic Regression, Random Forest, K-Nearest Neighbors). The prediction is based on the provided input data.

## Features
- **Model Selection**: Users can choose from four machine learning models to predict loan approval.
- **Interactive Form**: Users input their personal and financial details using a user-friendly form.
- **Prediction Output**: Based on the input data, the selected model predicts loan approval.

## Requirements
- **Python**: 3.x
- **Flask**: Web framework for rendering the frontend and backend integration.
- **Scikit-learn**: Machine learning library for model predictions.
- **Pandas**: For data manipulation (if needed for model data).
- **Pickle**: For loading pre-trained models.

## Setup Instructions

### 1. Clone the Repository
To clone this repository to your local machine, run the following command:

```bash
git clone https://github.com/your-username/loan-approval-prediction.git
cd loan-approval-prediction

2. Install Dependencies
Create a virtual environment (optional but recommended) and activate it. Then install the necessary dependencies.

python -m venv venv
source venv/bin/activate  # For Mac/Linux
venv\Scripts\activate  # For Windows

Now, install the required Python libraries:
pip install -r requirements.txt

Here is a sample requirements.txt content:
Flask
scikit-learn
pandas

3. Add Pre-trained Models
Place your pre-trained model files (e.g., SVC.pkl, LogisticRegression.pkl, etc.) in the appropriate directory inside your project. You can load these models using Pickle or Joblib in your Flask app.

4. Run the Flask Application
Once the setup is complete, you can run the Flask application locally by using the following command:
python app.py

This will start a local server at http://127.0.0.1:5000/. Open the URL in your browser to interact with the Loan Approval Prediction form.
