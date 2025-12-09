# Time Series Final Project

This repository contains the code, experiments, and analysis for a final project involving time series forecasting and classification, focusing on financial data spanning from 1986 to 2018.

## 📌 Project Overview
The goal of this project is to evaluate different machine learning approaches for modeling financial time series, including:
- Temporal train/test splits that respect temporal ordering
- Labeling strategies for forecasting windows
- Evaluation of sequence embedding models
- Comparison of pooling strategies and classification performance


## 📊 Experiments Included
- Non-leaky train/validation/test splitting
- Shared label encoding across multiple columns
- Embedding generation using custom pipeline models
- Testing different pooling strategies such as mean, max, attention

## 📈 Results Summary
A full discussion and analysis of results can be found in the **Results & Discussion** section of the notebook, including:
- Model accuracy
- Impact of different window sizes
- Comparison of pooling strategies

## 🧠 Key Concepts Used
- Time series forecasting
- Cumulative returns and window labeling
- Neural sequence encoders
- DataLoader batching and padding in PyTorch

