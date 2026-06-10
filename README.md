# Goal-Based-Wealth-Management
This is a Streamlit-based sector allocation tool that enables users to determine optimal portfolio allocations across different market sectors. Using historical stock data from Yahoo Finance, the app organizes sectors into three distinct categories, each containing four sectors with tailored weights, to help align investment preferences with specific risk tolerances and investment durations.

# Scoring Methodology
Score Calculation: For each sector, a score is computed based on historical returns and volatility, adjusted for the selected risk level and time horizon.
Sorting and Allocation: Sectors are sorted by score, and the top twelve sectors are divided into three categories of four sectors each.
Weight Normalization: Within each category, sector weights are normalized to sum to 1, allowing clear insights into allocation distribution.
# Installation
To set up and run this project locally, follow these steps:

# Install Requirements: Install the required Python packages:

pip install -r requirements.txt
# Requirements include:

streamlit
yfinance
numpy
pandas
Run the App: Start the Streamlit app with:

streamlit run main.py
