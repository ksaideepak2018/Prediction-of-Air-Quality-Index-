# Prediction-of-Air-Quality-Index

This project analyzes real-time air quality data to explore pollution patterns, visualize AQI trends, and apply clustering techniques for location-based analysis. It uses data collected via external APIs, along with machine learning techniques such as PCA and K-Means clustering.

## Project Overview

The notebook demonstrates the end-to-end process of:
- Fetching current air quality and geolocation data via APIs
- Cleaning and standardizing environmental data
- Performing exploratory data analysis (EDA)
- Applying dimensionality reduction with PCA
- Clustering regions based on air quality metrics using K-Means

## Technologies Used

- Python
- `requests` – API integration
- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Visualization
- `scikit-learn` – PCA, K-Means clustering
- `mpl_toolkits` – 3D visualization

## Features

- Extract air quality data by location using a RapidAPI geolocation endpoint
- Visualize pollutant levels and AQI trends across different geographies
- Use **PCA** to reduce dimensionality and **K-Means** to identify pollution clusters
- Display insights using 2D and 3D plots


## How to Run

1. Clone the repository
2. Set your RapidAPI credentials in the notebook
3. Run all cells in sequence to fetch, process, and visualize air quality data
