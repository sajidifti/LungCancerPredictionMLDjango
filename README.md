# Lung Cancer Prediction with Machine Learning Models

## Overview

This project is focused on predicting lung cancer using machine learning models, implemented within a Django web application. The models used for prediction include Logistic Regression, Gaussian Naive Bayes, and Decision Tree, with the Decision Tree model being the final choice for the Django app.

## Machine Learning Models

### 1. Logistic Regression

Logistic Regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable. It is used to predict the probability of a binary outcome based on one or more predictor variables.

### 2. Gaussian Naive Bayes

Gaussian Naive Bayes is a variant of the Naive Bayes algorithm. It assumes that the continuous values associated with each feature are distributed according to a Gaussian (normal) distribution.

### 3. Decision Tree

Decision Tree is a non-parametric supervised learning method used for classification and regression. It splits the data into subsets based on the value of input features, creating a tree-like model of decisions. This model was chosen as the final model for the Django application due to its interpretability and performance.

## Django Application

The Django application provides a user-friendly interface for predicting lung cancer. Users can input their medical data, and the app will use the Decision Tree model to predict the likelihood of having lung cancer.

### Key Files

- `views.py`: Contains the logic for handling user inputs and displaying predictions.
- `forms.py`: Defines the forms used for inputting data.
- `models.py`: Defines any database models used in the application.
- `templates/`: Contains the HTML templates for rendering the web pages.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/sajidifti/LungCancerPredictionMLDjango.git
    cd LungCancerPrediction
    ```

2. **Create a virtual environment and activate it:**

    ```bash
    python3 -m venv env
    source env/bin/activate
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Django development server:**

    ```bash
    python manage.py runserver
    ```

5. **Access the application:**
    Open your web browser and navigate to `http://127.0.0.1:8000/`.

## Usage

1. **Input Data:**
    Navigate to the prediction form and input the required medical data.

2. **Get Prediction:**
    Submit the form to get the lung cancer prediction based on the Decision Tree model.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

I would like to thank all contributors and the open-source community for their invaluable support and resources.

---

This project is intended for educational purposes and should not be used as a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or other qualified health provider with any questions you may have regarding a medical condition.
