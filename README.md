Global Cost of Living & Affordability — EDA

This project analyzes the global cost of living using The Economist’s Big Mac Index combined with World Bank indicators.

The goal is to explore how Big Mac prices relate to GDP per capita, inflation, unemployment, and income inequality across different countries and regions. Through data cleaning, visualization, and simple modeling, the project highlights affordability patterns and global economic differences.

Project Summary

Data Sources:

Big Mac Index (The Economist, 2000–latest year)

World Bank Indicators via wbgapi

Dataset Size: ~1,900 rows × 21 features

Countries: 73

Indicators Used: GDP per capita, inflation, unemployment, urban %, population, and Gini index

Key Steps

Data Cleaning & Preparation

Loaded data directly from The Economist’s GitHub and the World Bank API.

Standardized dates, country codes, and currency fields.

Merged both datasets by ISO3 and year.

Filled missing values within each country.

Feature Engineering

Visualization

Statistical Modeling

Results

Global Mean Big Mac Price: $4.96

Median Price: $3.69

Average Price Growth (2000–2022): ~3.6% per year

Correlation (log price vs log GDP): 0.20 (weak positive)

Most Volatile Prices: Lebanon, Venezuela, Argentina

93% of countries have Big Macs cheaper than the U.S.

Summary

This project connects global economics and data visualization in an approachable way.

By analyzing burger prices alongside World Bank indicators, it highlights how affordability varies around the world — showing that something as simple as a Big Mac can reveal real economic differences in income, inflation, and purchasing power.
