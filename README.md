# Heart Disease Prediction Web App

This is a web application developed with Django that predicts the likelihood of heart disease based on user input.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Heart Disease Prediction Web App is designed to provide users with an estimation of their risk for heart disease. It takes various input parameters such as age, gender, blood pressure, cholesterol level, etc., and uses a machine learning model to predict the likelihood of heart disease.

## Features
- User-friendly interface for inputting necessary information.
- Utilizes a trained machine learning model to make predictions.
- Displays the predicted probability of heart disease along with an interpretive message.
- Provides feedback on the significance of each input feature.

## Installation
1. Clone the repository:
 ```
 git clone https://github.com/alaminmagaga/heart-disease-prediction-django-web-app.git
 ```
3. Navigate to the project directory: 
```
cd heart-disease-prediction-django-web-app
```
5. Create a virtual environment: 
```
python -m venv venv
```
7. Activate the virtual environment:
   - For Windows: 
    ```
    venv\Scripts\activate
    ```
   - For Unix or Linux: 
    ```
    source venv/bin/activate
    ```
8. Install the required dependencies: 
 ```
 pip install -r requirements.txt
 ```
10. Run the application: 
 ```python manage.py runserver
 
 ```

## Usage
1. Open your web browser and go to `http://localhost:8000` (or the appropriate address and port).
2. Fill out the form with the relevant information.
3. Click the "Predict" button to receive the prediction.
4. The result will be displayed on the screen along with an interpretive message.

## Technologies Used
- Django: Python web framework for building the application.
- Python: Programming language used for development.
- Machine Learning: Used to train the heart disease prediction model.
- HTML/CSS: Markup and styling for the web interface.

## Contributing
Contributions are welcome! If you'd like to contribute to the project, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Make your modifications and commit them: `git commit -am 'Add some feature'`
4. Push the branch to your forked repository: `git push origin feature-name`
5. Submit a pull request to the original repository.

