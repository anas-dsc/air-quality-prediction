# Air Quality Prediction Using Machine Learning

## Project Overview

This project focuses on predicting Carbon Monoxide (CO) concentration using environmental sensor data and machine learning techniques.

The project applies data preprocessing, exploratory data analysis (EDA), feature importance analysis, and regression modeling to forecast air pollution levels.

---

## Objectives

- Analyze environmental sensor data
- Predict CO concentration accurately
- Compare multiple machine learning algorithms
- Evaluate model performance using regression metrics
- Visualize relationships between environmental variables

---

## Dataset Information

- Source: UCI Machine Learning Repository
- Records: 9358 hourly observations
- Location: Italy
- Time Period: March 2004 – February 2005

### Key Features
- CO(GT)
- NO₂(GT)
- Temperature
- Relative Humidity
- Benzene Concentration
- Sensor Measurements

---

## Machine Learning Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

---

## Performance Results

| Model | Performance |
|---|---|
| Random Forest | Best Overall Performance |
| Gradient Boosting | Strong Performance |
| Decision Tree | Moderate Performance |
| Linear Regression | Baseline Model |

### Best Model Metrics
- R² Score: 0.8484
- MSE: 0.2615

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Repository Structure

```bash
air-quality-prediction/
│
├── notebooks/
│   └── Air_Quality_Analysis.ipynb
│
├── presentation/
│   └── Air_Quality_Project_Presentation.pptx
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

## Project Files

| File | Description |
|---|---|
| Air_Quality_Analysis.ipynb | Complete analysis and machine learning workflow |
| Air_Quality_Project_Presentation.pptx | Final project presentation |

---

## Author

Anas Ebrahim Shabalah

---

## License

This project is licensed under the MIT License.
