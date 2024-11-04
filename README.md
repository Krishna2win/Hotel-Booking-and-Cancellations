# Hotel Booking and Cancellations

This project analyzes hotel booking data to predict cancellations, providing insights into customer behavior and factors influencing cancellations. The goal is to help hotels optimize resource management and improve revenue forecasting.

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [How to Use](#how-to-use)
- [References](#references)

## Introduction
Hotel cancellations present a challenge for revenue management and operational efficiency. This project uses machine learning to predict the likelihood of a booking being canceled, enabling proactive measures.

## Data Description
The dataset consists of booking information from two hotels in Portugal:
- **Resort Hotel (H1)**: 40,060 observations
- **City Hotel (H2)**: 79,330 observations
- **Features**: Includes details such as lead time, deposit type, customer type, number of special requests, and more.

## Methodology
1. **Data Preprocessing**: Handling missing values, encoding categorical features, and feature scaling.
2. **Exploratory Data Analysis (EDA)**: Identifying patterns and correlations.
3. **Modeling**: Building and evaluating different machine learning models.

## Exploratory Data Analysis (EDA)
Key insights from EDA:
- Longer lead times are associated with higher cancellation rates.
- Fewer special requests correlate with higher likelihoods of cancellation.
- Non-refundable deposits significantly reduce cancellation rates.

## Modeling
We experimented with several models:
- **Logistic Regression**
- **Decision Tree Classifier**

Evaluation metrics include accuracy, F1 score, precision, and recall.

## Results
- The best-performing model achieved 97% accuracy, effectively predicting cancellations.
- Key features influencing cancellations: lead time, deposit type, special requests, and customer type.

## Future Improvements
- Incorporate additional features like weather or event data.
- Use more advanced ensemble techniques for better performance.
- Develop a real-time dashboard for cancellation prediction.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Krishna2win/Hotel-Booking-and-Cancellations.git
2. **Navigate to the project directory**:
   ```bash
   cd Hotel-Booking-and-Cancellations
2. **Run the Jupyter Notebook**:
   ```bash
   Jupyter Notebook
