# datafun-07-applied

## Project Purpose
This project is focused on applying machine learning techniques, including linear regression, using Jupyter notebooks and Python libraries.

## Virtual Environment Setup

To keep dependencies organized, this project uses a local Python virtual environment.

### Steps to Create and Activate the Virtual Environment

1. Create the virtual environment:
   ```bash
   python3 -m venv .venv

2. Activate the virtual environment:
On macOS/Linux:
source .venv/bin/activate

On Windows (PowerShell):
.venv\Scripts\Activate.ps1

3. Upgrade pip and install required packages:

python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install jupyterlab numpy pandas pyarrow matplotlib seaborn scipy

## Running the Project
After activating the virtual environment, launch JupyterLab by running:jupyter lab

## Git Workflow Commands

git add .
git commit -m "Initial project setup with virtual environment and dependencies"
git push -u origin main




# Predictive Machine Learning Project - NYC January Temperatures

**Author:** Blessing Aganaga  
**Repository:** [datafun-07-applied](https://github.com/teflxndxn/datafun-07-applied.git)  

---

## Project Overview

This project explores historic average high temperatures in New York City during January from 1895 to 2018. Using linear regression models, it predicts the average January high temperature for 2024. The goal is to practice predictive machine learning using Python, Pandas, SciPy, and scikit-learn.

---

## Data

- Source: CSV file `data/ave_hi_nyc_jan_1895-2018.csv`  
- Contains yearly average high temperatures in NYC for January from 1895 to 2018.

---

## Project Structure

- **Part 1:** Visualize the linear relationship between Celsius and Fahrenheit to understand line equations.  
- **Part 2:** Perform linear regression with SciPy's `linregress` to predict 2024 temperature.  
- **Part 3:** Use scikit-learn’s `LinearRegression` with train-test split, evaluate model metrics, and predict 2024 temperature.  
- **Part 4:** Plot regression results, actual data points, and predictions.  

---

## How to Run

1. Clone the repo:  
   ```bash
   git clone https://github.com/teflxndxn/datafun-07-applied.git
   cd datafun-07-applied

Make sure dependencies are installed:
pip install -r requirements.txt

Run the Jupyter notebook or Python scripts for each part to reproduce the analysis.

## Key Findings

The linear regression model predicts an average high temperature of approximately 38.05°F for NYC in January 2024.
Model evaluation metrics (MAE, MSE, R²) suggest the model has some limitations and room for improvement but captures the general trend.
Historical data shows a gradual increase in average January temperatures over the years.