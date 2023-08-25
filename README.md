# Cryptocurrency Exploratory Data Analysis (EDA)

This repository contains exploratory data analysis (EDA) for cryptocurrencies. The EDA is performed on data extracted from CoinGecko using an ETL process. The analysis focuses on defining Key Performance Indicators (KPIs) to aid decision-making in the cryptocurrency market.

## Contents

- [ETL.ipynb](ETL.ipynb): Jupyter Notebook for extracting data from CoinGecko and preparing it for analysis.
- [EDA.ipynb](EDA.ipynb): Jupyter Notebook for exploratory data analysis, including the development of KPIs.
- [data/](data/): Folder containing the extracted and preprocessed data.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/someonefrom93/PIDA_J_DIEGO.git
   cd PIDA_J_DIEGO

Install the required packages by creating a virtual environment and installing dependencies:

`python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
pip install -r requirements.txt`

## Open and run the ETL and EDA notebooks in a Jupyter environment.

About the Analysis
The ETL.ipynb notebook extracts data from CoinGecko API and preprocesses it for analysis.
The EDA.ipynb notebook focuses on exploratory data analysis, including the creation and analysis of Key Performance Indicators (KPIs).
KPIs developed include Sharpe Ratio, Price-to-Market Capitalization Ratio, and Volume-to-Market Cap Ratio.


![pipeline](images/readme_images/pipeline.JPG)