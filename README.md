# Temperature Prediction using Air Quality Index Dataset

This project implements a machine learning model to predict temperature using air quality index data from the Sylhet region. The project compares multiple regression algorithms to determine the best performing model for temperature prediction.

## Author Information

- **Name**: Shahriar Alom
- **Email**: shahriaralomshakil@gmail.com
- **Student ID**: 2202043
- **Batch**: 49
- **Serial No**: 01

## Dataset

The dataset used in this project contains air quality index data with temperature measurements from the Sylhet region.

**Dataset Link**: [Air Quality Index Dataset](https://docs.google.com/spreadsheets/d/1QoXjVKVI-VfDB9LuV2rIj19BZ2dWm59A/edit?usp=sharing&ouid=108196870504177501321&rtpof=true&sd=true)

## Project Overview

This project focuses on predicting temperature values using various environmental and air quality features. The implementation includes:

- Data preprocessing and cleaning
- Feature engineering (numerical and categorical)
- Model training and evaluation
- Model comparison and visualization

## Features

The project implements the following machine learning pipeline:

1. **Data Loading and Exploration**
   - Loading Excel data with multiple sheets
   - Focusing on Sylhet region data
   - Data inspection and quality assessment

2. **Data Preprocessing**
   - Handling missing values using SimpleImputer
   - Separating numerical and categorical features
   - Data type conversion and standardization

3. **Feature Engineering**
   - StandardScaler for numerical features
   - OrdinalEncoder for categorical features
   - Train-validation-test split (64%-16%-20%)

4. **Model Implementation**
   - Random Forest Regressor (primary model)
   - Linear Regression
   - Decision Tree Regressor

5. **Model Evaluation**
   - RMSE (Root Mean Square Error)
   - R² Score
   - Cross-model performance comparison

6. **Visualization**
   - Model performance comparison charts
   - Aesthetic bar plots with custom styling

## Dependencies

```python
pandas
numpy
scikit-learn
matplotlib
```

## Key Components

### Data Processing
- **Missing Value Handling**: Drops rows with null values
- **Feature Separation**: Automatic detection of numerical vs categorical columns
- **Scaling**: StandardScaler for numerical features
- **Encoding**: OrdinalEncoder for categorical features

### Models Evaluated
1. **Random Forest Regressor**: Main model with 100 estimators
2. **Linear Regression**: Baseline comparison model
3. **Decision Tree Regressor**: Tree-based alternative

### Performance Metrics
- **RMSE**: Measures prediction accuracy
- **R² Score**: Explains variance in temperature predictions
- **Comparative Analysis**: Side-by-side model performance

## Project Structure

```
Temperature_Prediction_2202043_Shahriar_Alom_Batch_49_01/
├── Temperature_Prediction_2202043.ipynb    # Main notebook file
├── README.md                               # This file
└── air_quality_index_dataset.xlsx         # Dataset (referenced)
```

## Usage

1. **Data Loading**: The notebook loads data from an Excel file with multiple sheets
2. **Data Preprocessing**: Automated cleaning and feature preparation
3. **Model Training**: Multiple algorithms trained on the same dataset
4. **Evaluation**: Comprehensive performance comparison
5. **Prediction**: Single-row prediction example included

## Results

The project compares three different regression models:
- Random Forest Regressor
- Decision Tree Regressor  
- Linear Regression

Performance metrics are calculated and visualized to determine the best performing model for temperature prediction.

## Visualization

The project includes:
- Model performance comparison bar charts
- Custom styling with pastel color schemes
- Professional presentation of results

## Google Colab Integration

The notebook includes a Google Colab badge for easy cloud execution:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ShahriarAlomShakil/Temperature_Prediction_2202043_Shahriar_Alom_Batch_49_01/blob/main/Temperature_Prediction_2202043.ipynb)

## How to Run

1. Clone or download the repository
2. Ensure all dependencies are installed
3. Place the dataset file in the appropriate location
4. Run the Jupyter notebook cells sequentially
5. View results and model comparisons

## Contact

For questions or collaborations, please contact:
- **Email**: shahriaralomshakil@gmail.com
- **LinkedIn**: [Shahriar Alom Shakil](https://www.linkedin.com/in/shahriaralomshakil/)
- **Fiverr**: [Professional Services](https://www.fiverr.com/s/WEvxaNB)
- **Resume**: [View Resume](https://drive.google.com/file/d/12YsBEytUK_KE1dXJOkbrFC2xLlAtsh_5/view?usp=drive_link)

---

*This project is part of an academic assignment for machine learning coursework.*
