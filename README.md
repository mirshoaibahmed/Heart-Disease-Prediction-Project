# Python Heart Disease Prediction Project

## Project Description

This project is a machine learning-based approach to predict heart disease using a dataset of patient information. The goal is to build a classification model that can accurately identify individuals with a high risk of heart disease based on their health metrics.

## Technologies and Libraries

* **Python:** The core programming language.
* **Google Colab:** The development environment used for the analysis.
* **Pandas:** For data handling and analysis.
* **Scikit-learn:** Used to build the machine learning model.

## Dataset

The project uses the `heart.csv` dataset, which contains various health metrics, including age, gender, cholesterol levels, and heart rate, along with a target variable indicating the presence of heart disease.

## Key Steps

1.  **Data Loading and Initial Analysis:** The `heart.csv` file was loaded into a Pandas DataFrame, and initial analysis was performed to understand the structure of the data.
2.  **Model Building:** A **Naive Bayes classifier** was chosen to build the prediction model.
3.  **Model Evaluation:** The model's performance was evaluated using **10-fold cross-validation** to ensure its accuracy and reliability.

## Results

The model achieved an average accuracy of [Insert your average accuracy here from the notebook output] across 10 folds.

## How to Run the Project

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/mirshoaibahmed/Heart-Disease-Prediction-Project.git
    ```
2.  Navigate to the project directory.
3.  Ensure you have Python and the required libraries installed.
4.  Open the Google Colab file in your environment and run the cells sequentially to see the analysis and model in action.
