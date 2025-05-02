# House Price Prediction

This repository contains an end-to-end machine learning project for predicting house prices. The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation. It is designed to demonstrate the complete lifecycle of a machine learning project. [Project Deployed Link](https://housepriceprediction-medplmmtpbacvnyt5akimp.streamlit.app/).

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Directory Structure](#directory-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#Demo)
- [Technologies Used](#technologies-used)

---

## Project Overview

The goal of this project is to predict house prices based on various features such as location, size, and other relevant attributes. The project uses machine learning models to analyze the data and provide accurate predictions.

---

## Features

- **Data Preprocessing**: Handles missing values, encodes categorical variables, and scales numerical features.
- **Exploratory Data Analysis (EDA)**: Visualizes data distributions, correlations, and trends.
- **Model Training**: Implements and trains machine learning models.
- **Model Evaluation**: Evaluates models using metrics like RMSE, MAE, and R².
- **Pipeline Automation**: Automates the entire process using modular components.

---

## Directory Structure

```
House_price_prediction/
├── app.py                # Main application file
├── Dockerfile            # Docker configuration
├── README.md             # Project documentation
├── requirements.txt      # Python dependencies
├── setup.py              # Package setup
├── artifacts/            # Stores model and preprocessed data
│   ├── data.csv
│   ├── model.pkl
│   ├── preprocessor.pkl
│   ├── train.csv
│   └── test.csv
├── notebook/             # Jupyter notebooks for EDA and modeling
│   ├── EDA.ipynb
│   ├── MODEL.ipynb
│   └── catboost_info/
├── src/                  # Source code
│   ├── __init__.py
│   ├── exception.py      # Custom exception handling
│   ├── logger.py         # Logging utility
│   ├── utils.py          # Helper functions
│   ├── components/       # Modular components for the pipeline
│   └── pipeline/         # Pipeline implementation


```


---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/House_price_prediction.git
   cd House_price_prediction

2. Create a virtual environment:

```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the dependencies:

```
pip install -r requirements.txt
```

4. Install the project as a package:

```
pip install -e .
```

# Usage

1. Run the application:

```
python app.py 
```

2. Open the application in your browser:
```
http://localhost:5000
```
```
http://127.0.0.1:5000
```

3. Use the web interface to upload data and get predictions.

# Demo

![House_price_project](https://github.com/user-attachments/assets/dd7620cc-c7d4-412f-9968-b47d506c3814)


# Technologies Used

- Programming Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Framework: Streamlit (for web application)
- Containerization: Docker


