# Web3 Trading & Sentiment Analysis

A Python-based data analysis tool that examines the relationship between Web3 trader performance and crypto market sentiment (Fear & Greed Index).

## Overview

This project merges historical trading data with daily sentiment scores to uncover patterns in profitability, leverage usage, and risk across different market conditions.

## Features

- Data cleaning and preprocessing for trading and sentiment datasets
- Merged analysis combining trader behavior with market psychology
- 11 automated visualizations including an executive dashboard
- Statistical summaries and insights export

## Project Structure

ds_project/
├── csv_files/          # Input data and processed outputs
├── outputs/            # Generated charts and reports
└── analysis.ipynb      # Main notebook

## Requirements


python >= 3.7
pandas
numpy
matplotlib
seaborn

## Usage

1. Place input files (`historical_trader_data.csv`, `fear_greed_index.csv`) in the `csv_files/` folder
2. Run the notebook or script
3. View outputs in the `outputs/` folder

## Outputs

- Daily volume trends
- PnL distribution analysis
- Sentiment-based performance breakdown
- Correlation heatmaps
- Top trader rankings
- Executive summary dashboard
