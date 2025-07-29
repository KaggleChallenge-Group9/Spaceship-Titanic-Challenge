# Spaceship-Titanic-Challenge

This repository contains a workflow for the **Spaceship Titanic** Kaggle competition, developed as part of the 7PAM2015 Research Methods in Data Science module.

# Team Information

**Group :** Group 9
- **GitHub Repo:** [GitHub Link](https://github.com/KaggleChallenge-Group9/Spaceship-Titanic-Challenge)  
- **Google Colab Notebook:** [Colab Link](https://colab.research.google.com/drive/1hz_5xvlN9PqSKk90i8JNYxFYfH7eqqBH)

# Objective

Predict whether a passenger was **transported to another dimension** during a space voyage using the given dataset.

# Project Structure

**Exploratory Data Analysis (EDA)**
- Summary statistics and data types
- Visualised missing values
- Target variable distribution
- Categorical distributions (e.g., `HomePlanet`, `CryoSleep`, `Cabin` via treemaps)

### 2. Data Preprocessing

**Preprocessing**
- Missing value imputation (using mean, median, mode)
- Cabin data splitting and transformation
- Label encoding of categorical variables

**Feature selection**
- 13 input features selected, such as Age, VIP status, services used, and Cabin metadata

**Model training and development**
- Logistic Regression and Random Forest
- Train/validation split (80 % and 20%)
- GridSearchCV for hyperparameter tuning
- - Neural Network using TensorFlow/Keras
- Sequential model with:
  - Dense + BatchNormalization + Dropout layers
  - ReLU activations and final sigmoid layer
- Training with `binary_crossentropy` loss and `adam` optimiser

**Evaluation**
- Achieved accuracy and loss analysis on training/validation sets
- Generated predictions for the test set
- Exported submission for Kaggle

**Technologies used**
- Python, Pandas, NumPy
- Seaborn, Matplotlib, Squarify
- Scikit-learn, TensorFlow/Keras
- Google Colab, GitHub



