# Regression Task 1 - House Price Prediction

![House Price Model Screenshot](https://via.placeholder.com/800x400?text=House+Price+Prediction+Model)

A machine learning regression project for predicting average residential unit prices using real estate data and Python.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dataset Overview](#dataset-overview)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
This project aims to develop a regression pipeline to estimate residential unit prices based on historical and property-related data. It involves loading an Excel dataset, preprocessing, feature engineering, training multiple regression models, and evaluating their performance.

## Features
- Load and clean real estate dataset
- Handle missing data and categorical variables
- Feature scaling using StandardScaler
- Train and compare multiple regression models:
  - Linear Regression
  - Ridge Regression
  - Random Forest Regressor
- Evaluate models using MSE, MAE, and R²
- Save predictions and visualize results

## Technologies Used
- **Language**: Python 3.x
- **Libraries**:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - openpyxl (for Excel support)
  - joblib (for saving models)

## Getting Started

### Prerequisites
- Python 3.8 or later
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/AliAbdallah21/regression-task-1.git
cd regression-task-1
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

If `requirements.txt` is not provided, install manually:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl joblib
```

## Usage

1. Open the notebook:
```bash
jupyter notebook regression_task1.ipynb
```

2. Follow the cells in the notebook to:
   - Load your Excel dataset
   - Preprocess and encode the data
   - Train regression models
   - Evaluate model performance
   - Save and visualize predictions

## Project Structure
```
.
├── regression_task1.ipynb     # Main Jupyter Notebook
├── data/                      # (Optional) Folder to store dataset
│   └── your_data.xlsx         # Your Excel dataset
├── models/                    # (Optional) Folder to save trained models
├── README.md                  # This file
└── requirements.txt           # List of required Python packages
```

## Dataset Overview
Your dataset should include features such as:
- Property Type
- Location
- Area in square meters or feet
- Number of rooms
- Year of construction or sale
- Final price (target variable)

Make sure all columns are properly labeled and missing values are handled in preprocessing.

## Contributing

1. Fork this repository
2. Create your feature branch:
```bash
git checkout -b feature/your-feature-name
```
3. Commit your changes:
```bash
git commit -m "Add your feature"
```
4. Push to the branch:
```bash
git push origin feature/your-feature-name
```
5. Open a Pull Request

## License
MIT © 2025 Ali Abdallah

## Contact
Ali Abdallah  
📧 aliabdalla2110@gmail.com  
GitHub: [https://github.com/AliAbdallah21](https://github.com/AliAbdallah21)  
Project Link: [https://github.com/AliAbdallah21/regression-task-1](https://github.com/AliAbdallah21/regression-task-1)
