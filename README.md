# Crop_Recommendation

Crop Recommendation System using Flask and Machine Learning

## Overview

The Crop Recommendation System is a web application that helps farmers determine the most suitable crop to cultivate based on the temperature input. This system uses a machine learning model trained on agricultural data to make accurate crop recommendations.

## Features

Accepts temperature as user input.

Predicts the most suitable crop to cultivate based on the given temperature.

Built using Flask for the web framework.

Uses a trained Machine Learning model for predictions.

## Technologies Used

Python

Flask (for web framework)

Scikit-learn (for ML model)

Pandas & NumPy (for data handling)

HTML, CSS, JavaScript (for frontend)

## Installation

Prerequisites

Make sure you have Python installed (preferably Python 3.7 or later). Install required dependencies using:

pip install flask numpy pandas scikit-learn

Clone the Repository

git clone https://github.com/your-repo/crop-recommendation.git
cd crop-recommendation

Run the Application

python app.py

The application will start running on http://127.0.0.1:5000/.

## Usage

Open the web browser and go to http://127.0.0.1:5000/.

Enter the temperature in the input field.

Click the Predict button.

The system will display the most suitable crop for cultivation.

## Project Structure

├── static
│   ├── styles.css
│   ├── script.js
├── templates
│   ├── index.html
├── model
│   ├── crop_model.pkl  # Trained ML model
├── app.py  # Flask application
├── requirements.txt
└── README.md

## ML Model Training

The machine learning model is trained using a dataset containing:

Temperature

Humidity

Soil Type

Crop suitability labels

## We use a RandomForestClassifier from Scikit-learn to predict the best crop based on temperature input.

Future Enhancements

Include humidity and soil type as additional input parameters.

Deploy the model on a cloud platform (AWS, Heroku, or Render).

Improve the UI with better design and interactivity.

Contributing

Feel free to fork this repository and submit a pull request with improvements!

License

This project is licensed under the MIT License.

