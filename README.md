🧠 **Dynamic Soft-Thresholding for Feature Selection in Regression**

📌** Project Overview**

This project applies numerical optimization techniques to improve regression models for housing price prediction.
It compares multiple machine learning algorithms and introduces Dynamic Soft-Thresholding to optimize the LASSO regularization parameter (α) for better feature selection and prediction accuracy.

🎯** Objectives**

Implement Linear, Ridge, and LASSO Regression

Apply Dynamic LASSO Optimization

Perform feature selection using LASSO

Compare model performance using Mean Squared Error (MSE)

Visualize results using graphs

🗂** Dataset**

**Dataset**: 
Housing Price Dataset

Total Samples: 545

Total Features: 13

Target Variable: Price

**Features include**:
Area


Bedrooms

Bathrooms

Floors

Parking

🏗** Project Structure**

project-folder/

│

├── dataset/

│   └── housing.csv

│

├── code/

│   └── model.py

│

├── graph/

│   └── model_comparison.png

│

├── main.py

├── requirements.txt

└── README.md

⚙️ **Installation**

Install the required libraries:

pip install -r requirements.txt


▶️** Running the Project**

Run the project using:

python main.py

📊** Output**

The program will:
✔ Train regression models
✔ Compare model performance
✔ Generate a comparison graph

**Saved graph location:**

graph/model_comparison.png

📈** Model Comparison**
Model	Mean Squared Error

Linear Regression	0.17

Ridge Regression	0.18

LASSO Regression	0.51

Dynamic LASSO	0.51

🛠** Technologies Used**

Python

Pandas

NumPy

Scikit-Learn

Matplotlib

VS Code

Air Conditioning

Furnishing Status
