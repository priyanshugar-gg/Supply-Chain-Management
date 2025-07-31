# Sales Prediction in Supply Chain Management

## Project Overview
This project aims to analyze and predict sales trends using a dataset related to Supply Chain Management (SCM). The dataset is processed to visualize trends, identify patterns, and provide insights into sales performance.

## Dataset
- The project uses `SCM Dataset.csv` as the primary dataset.
- Data is loaded, cleaned, and visualized using various statistical and machine learning techniques.

## Features & Functionality
- **Data Preprocessing**: Handles missing values, encodes categorical data, and prepares the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Generates histograms, box plots, and scatter plots to analyze sales trends.
- **Prediction Models**: 
  - Implemented **Time Series Analysis** using models such as **ARIMA** and **SARIMA** to forecast sales trends.
  - Evaluated model performance using metrics such as **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)**.

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/jatin019/Suppply-Chain-Management-Project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Suppy-Chain-Management-Project
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   *(Ensure you have Python installed before running the command.)*

## How to Use
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Run the `Main Code.ipynb` notebook step by step to process the dataset, visualize results, and apply time series forecasting.

## Dependencies
The project requires the following Python libraries:
- `pandas` (for data handling)
- `matplotlib` and `seaborn` (for visualization)
- `numpy` (for numerical computations)
- `scikit-learn` (for predictive modeling)
- `statsmodels` (for time series analysis)

To install them manually, run:
```bash
pip install pandas matplotlib seaborn numpy scikit-learn statsmodels
```




