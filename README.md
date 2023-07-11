# Stellar-Classification

This repository contains an in-depth analysis and classification of stellar objects using various machine learning algorithms. The goal of this project is to accurately classify stars based on their features.

## Project Overview

In this project, I performed exploratory data analysis (EDA) to gain insights into the dataset and understand the distribution of different stellar features. The EDA process helps understand the data and identify any patterns or relationships that may exist.

## Classification Algorithms Used

I employed a range of popular machine learning algorithms to classify stellar objects. The algorithms used in this project include:

- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Trees
- Random Forest
- XGBoost

For each algorithm, appropriate preprocessing techniques were applied, model was trained on the labeled stellar dataset, performance evaluated using various evaluation metrics.

## Evaluation Metrics

To assess the performance of each classification model, a set of evaluation metrics were utilized, including:

- Accuracy: measures the overall correctness of the classification results.
- Precision: measures the proportion of correctly predicted positive instances out of all predicted positives.
- Recall: measures the proportion of correctly predicted positive instances out of all actual positives.
- F1-score: provides a balanced measure of precision and recall.
- Confusion Matrix: presents a detailed breakdown of the model's predictions for each class.

The evaluation results for each algorithm are included in the repository, providing insights into their individual strengths and weaknesses in stellar classification.


## Feature Engineering

The feature engineering process for stellar classification incorporated the following important features:

- **Alpha (Right Ascension angle)**: Right Ascension is a celestial coordinate that represents the angular distance of an object eastward along the celestial equator from a specific reference point (usually the vernal equinox). It helps in locating objects in the sky and is essential for positional analysis.

- **Delta (Declination angle)**: Declination is a celestial coordinate that represents the angular distance of an object north or south of the celestial equator. It complements Right Ascension and together helps precisely locate celestial objects in the sky.

- **Ultraviolet (u)**: The Ultraviolet filter measures the flux or intensity of light in the ultraviolet part of the electromagnetic spectrum. It captures information about the emission or absorption of ultraviolet radiation by the objects being observed. This feature can be useful in characterizing the spectral properties of stars, galaxies, or quasars.

- **Green (g), Red (r), Near Infrared (i), and Infrared (z)**: These filters represent different bands of the electromagnetic spectrum and measure the flux or intensity of light in specific wavelength ranges. They capture information about the objects' spectral energy distribution across different wavelengths. By analyzing the intensity in different filters, we can gain insights into the color, temperature, and composition of the objects.

- **Redshift**: Redshift is a measure of how much the wavelength of light emitted by an object has shifted towards longer (redder) wavelengths due to the expansion of the universe. It provides information about the relative motion of the object and can be used to estimate the distance to the object. Redshift is particularly relevant for studying galaxies and quasars.

- **Plate**: The Plate ID is an identifier for each plate in the Sloan Digital Sky Survey (SDSS). SDSS is a large-scale astronomical survey that has mapped and analyzed a vast number of celestial objects. The Plate ID helps track and associate specific observations or data points with their corresponding plate in the survey.

By incorporating these features into the analysis and feature engineering process for stellar classification, we leveraged the spatial, spectral, and observational characteristics of celestial objects to improve the accuracy and effectiveness of the classification model.

