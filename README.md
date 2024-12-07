# Data Science Project Collection 📊💻

This repository contains a series of data science exercises and projects aimed at exploring various domains such as clustering, time series analysis, machine learning, and more. Each project focuses on specific techniques and real-world datasets.

## Table of Contents
- [Clustering Activities](#clustering-activities)
- [Data Wrangling Medicaid](#data-wrangling-medicaid)
- [Simulation and Hypothesis: Memberships](#simulation-and-hypothesis-memberships)
- [Time Series Analysis](#time-series-analysis)
- [Wine Quality Classification](#wine-quality-classification)

## Clustering Activities 🤖👟

In this project, we use the **k-means clustering algorithm** to analyze time series data collected from wearable devices during activities like sleeping, running, and walking.

- **Dataset**: `data/activity.csv`
- **Goal**: Identify the number of activities and group individuals into clusters based on their activity patterns.
- **Challenge**: Data inconsistency exists—one cohort sampled every second and another every 2 seconds.

### Steps
1. Read and inspect the dataset for missing values.
2. Perform clustering to uncover hidden patterns.
3. Visualize and interpret the results.

## Data Wrangling Medicaid 🏥💊

This exercise involves working with two datasets:
1. **IRS Statistics of Income (SOI)**
2. **Medicaid Data per State**

The goal is to create a summary table that explores medication costs per Medicaid enrollee by state.

- Answer questions such as:
  - What drugs contribute most to a state's spending?
  - Are there regional patterns in drug prescriptions?

### Outcome
Gain insights into healthcare spending and data wrangling skills crucial for real-world projects.

## Simulation and Hypothesis: Memberships 💻📈

This project models revenue for a membership-based training website.

- **Dataset**: `memberships_info.csv`
- **Goal**: Develop a generative model to predict revenue for the upcoming year.

### Key Factors
- Gender differences in training completion rates and dropout probabilities.
- Annual growth in memberships (13% increase, SD: 1.4%).
- Historical data insights for over 90,000 enrollees in 2021.

Use the model to estimate revenue trends and understand membership dynamics.

## Time Series Analysis 📅🔢

Analyze and generate synthetic time series data based on the following components:
1. **Trend**: Exponential growth function.
2. **Seasonality**: Quarterly sine wave.
3. **Noise**: Gaussian distribution.

### Steps
1. Compute and plot each component independently.
2. Combine the components to create the final time series.
3. Use `np.random.seed(42)` to ensure reproducibility.

### Visualize
The dataset spans 200 months, showcasing seasonal patterns and trends.

## Wine Quality Classification 🍷📊

Classify wine quality (scale: 0–10) using various machine learning models.

- **Dataset**: Contains features like acidity, density, etc.
- **Goal**: Build models to classify wine quality and evaluate performance.

### Models
1. **K-Nearest Neighbors (KNN)**
2. **Logistic Regression**
3. **Random Forest**
4. **XGBoost**

### Evaluation
- Compare models based on **classification accuracy**.
- Visualize confusion matrix heatmaps to analyze prediction quality.

## How to Use this Repository 📂🛠️

1. Clone the repository:
git clone https://github.com/data-science-notebooks

Happy coding! 🚀



