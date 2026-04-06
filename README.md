# BLEVE-Risk-Prediction-using-Machine-Learning
This project develops a machine learning pipeline to predict the risk of BLEVE (Boiling Liquid Expanding Vapor Explosion) incidents using structured industrial data. The objective is to build a reliable predictive model through data preprocessing, exploratory analysis, feature engineering, and model evaluation.

# Project Overview
BLEVE incidents can cause severe industrial accidents. This project applies machine learning techniques to analyze operational conditions and predict potential explosion risks. The solution focuses on building a clean and reproducible ML workflow suitable for real-world deployment.

# Features
- Data preprocessing and cleaning pipeline
- Exploratory Data Analysis (EDA)
- Handling missing values and categorical encoding
- Feature scaling and transformation
- Model training and evaluation
- Prediction generation for the test dataset
- Reproducible workflow

# Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Statsmodels

# Project-Structure
notebooks/ \n
src/ \n
outputs/ \n
report/ \n
requirements.txt \n
README.md

# How to Run
Clone the repo: git clone https://github.com/Minh410/BLEVE-Prediction-ML.git cd BLEVE-Prediction-ML
Install dependencies: pip install -r requirements.txt
Run the notebook: jupyter notebook notebooks/bleve_prediction.ipynb

# Results
The model was trained on the provided dataset and evaluated using appropriate classification metrics. Predictions for the test dataset are stored in:

outputs/prediction.csv

# Author
Minh Huan Huynh
Project from the Machine Learning Unit (Bachelor of Computing) at Curtin University 
