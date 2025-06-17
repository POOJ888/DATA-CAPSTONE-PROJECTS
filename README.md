# DATA-CAPSTONE-PROJECTS


This repository contains completed data analysis capstone projects using real-world datasets. Each project is presented as a Jupyter Notebook and walks through the steps of data loading, exploration, feature engineering, visualization, and insights.

## Contents

- `01-911 Calls Data Capstone Project.ipynb`  
  Analyzes 911 emergency call data to extract insights about call frequency, call types, geographic trends, and temporal patterns. Includes data cleaning, feature engineering, and visualization.

- `03-Finance Project.ipynb`  
  Explores historical stock price data for major banks, performing exploratory data analysis (EDA), calculating returns, and visualizing trends and relationships using financial time series techniques.

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Recommended: Set up a virtual environment

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/POOJ888/DATA-CAPSTONE-PROJECTS.git
   cd DATA-CAPSTONE-PROJECTS
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
   Or install packages individually:
   ```
   pip install numpy pandas matplotlib seaborn yfinance statsmodels
   ```

### Running the Notebooks

1. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```
2. Open any of the provided notebooks and run all cells in order.

## Project Overviews

### 911 Calls Data Capstone Project

- **Goal:** Understand trends and patterns in emergency 911 call data.
- **Key Steps:**
  - Load and clean the dataset
  - Extract new features (e.g., reason for call, date parts)
  - Visualize call frequency by reason, geography, and time
  - Identify top locations and most common emergencies
- **Output:** Visualizations and summary insights

### Finance Project

- **Goal:** Analyze historical stock data for major US banks.
- **Key Steps:**
  - Download stock data using yfinance
  - Calculate daily returns, visualize trends, and assess risk
  - Compare bank performance over time
  - Visualize pairwise relationships and distribution of returns
- **Output:** Financial charts, statistical summaries, and risk/return analysis

## Notes

- All code is commented and organized for clarity and reproducibility.
- If you encounter missing data errors, ensure data files are present or check the download code.
- Set random seeds where applicable for reproducibility.

## License

This project is licensed under the MIT License.

## Author

- [POOJ888](https://github.com/POOJ888)
