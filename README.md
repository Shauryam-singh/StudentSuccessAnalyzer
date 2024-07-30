# Student Success Analyzer

## Overview

The Student Success Analyzer is a machine learning-based application designed to predict a student's math score based on various input factors such as gender, race/ethnicity, parental level of education, lunch type, test preparation course, reading score, and writing score.

## Features

- Predicts a student's math score based on input data
- User-friendly web interface for inputting student data
- Uses Flask for web framework
- Utilizes machine learning models for prediction

## Installation

1. **Clone the repository:**
git clone https://github.com/Shauryam-singh/StudentSuccessAnalyzer.git
cd StudentSuccessAnalyzer

3. **Create a virtual environment:**
python -m venv venv
venv\Scripts\activate

4. **Install the required packages:**
pip install -r requirements.txt

5. **Run the application:**
python app.py

## Usage

1. **Home Page:** Navigate to `http://127.0.0.1:5000/` to access the home page.
2. **Prediction Page:** Navigate to `http://127.0.0.1:5000/predictdata` to access the prediction page.
Enter the required student information and click on "Predict your Maths Score" to get the predicted math score.

## Input Fields

- **Gender:** Male or Female
- **Race/Ethnicity:** Group A, Group B, Group C, Group D, Group E
- **Parental Level of Education:** Associate's Degree, Bachelor's Degree, High School, Master's Degree, Some College, Some High School
- **Lunch Type:** Free/Reduced or Standard
- **Test Preparation Course:** None or Completed
- **Reading Score:** Score out of 100
- **Writing Score:** Score out of 100

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions or feedback, please reach out to shauryamsingh9@gmail.com.
