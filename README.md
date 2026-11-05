# NASA C-MAPSS: Remaining Useful Life (RUL) Prediction

## Project Overview

This project focuses on predicting the Remaining Useful Life (RUL) of aircraft turbofan engines using the NASA C-MAPSS FD001 dataset.

Remaining Useful Life estimation is an important task in predictive maintenance. It helps estimate how many operational cycles remain before an engine reaches the end of its useful life, supporting maintenance planning and reducing unexpected failures.

## Objectives

- Explore and understand multivariate sensor time-series data.
- Analyze engine degradation patterns.
- Perform data preprocessing and feature engineering.
- Develop machine learning models for RUL prediction.
- Evaluate model performance using appropriate regression metrics.

## Dataset

**Dataset:** NASA C-MAPSS FD001

The dataset contains run-to-failure sensor measurements from simulated turbofan engines.

Files used:

- `train_FD001.txt`: Training engine trajectories.
- `test_FD001.txt`: Test engine trajectories.
- `RUL_FD001.txt`: Ground-truth RUL values for test engines.

Dataset source: [NASA Prognostics Data Repository](https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/)

## Project Structure

```text
NASA-CMAPSS-RUL/
├── fd001/
├── images/
├── notebooks/
│   └── RUL_Analysis.ipynb
├── reports/
├── README.md
├── requirements.txt
└── .gitignore
```

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

The project workflow includes:

1. Data loading and exploration
2. Exploratory Data Analysis (EDA)
3. Sensor behavior and degradation analysis
4. Data preprocessing
5. Feature engineering
6. Model development
7. Model evaluation

## Evaluation

Model performance is evaluated using regression metrics such as:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

Detailed analysis, implementation, visualizations, and experimental results are available in the Jupyter Notebook.

## Installation

Clone the repository:

```bash
git clone https://github.com/farhan0060/CMAPSS-RUL-Prediction.git
cd CMAPSS-RUL-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Notebook

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

`notebooks/RUL_Analysis.ipynb`

## Project Status

Completed experimental project. Further improvements and model comparisons may be added.

## Author

**Mohammad Farhan Alinia**

[GitHub Profile]https://github.com/farhan0060
