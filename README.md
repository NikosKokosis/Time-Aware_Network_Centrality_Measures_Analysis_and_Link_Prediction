# Temporal Network Analysis and Link Prediction

This repository contains Jupyter Notebooks for conducting temporal network analysis and link prediction within the network. The project is divided into several sections, each focusing on different approaches and methods for analyzing network dynamics and predicting connections.

## Project Overview

In this project, we explore the temporal dynamics of networks and link prediction. The primary objectives are as follows:

1. **Temporal Network Analysis**: Exploring the dynamics of a network over time, including the calculation of time-aware centrality metrics and identifying common nodes between successive time periods.

2. **Link Prediction**: Creating datasets for link prediction using various approaches and evaluating the performance of different models for predicting connections within the network.

## Section 1: Temporal Network Analysis

- **Temporal_Network_Analysis.ipynb**: This Jupyter Notebook explores two types of network analysis on temporal data, focusing on understanding network dynamics over different time periods.

    - Analysis 1: Time-Aware Network Centrality Measures.
    - Analysis 2: Common Nodes Between Successive Time Periods.

## Section 2: Data Creation and Link Prediction (1st Approach)

- **Data_Creation_1st_Approach.ipynb**: This notebook explains the first approach for creating a dataset for link prediction. It involves connecting less popular nodes to neighbors of more popular nodes to create a well-balanced dataset.

- **Link_Prediction_of_1st_Approach.ipynb**: This notebook explores link prediction using the dataset created using the 1st approach and evaluates the performance of Artificial Neural Networks (ANN) and Linear Regression models.

## Section 3: Data Creation and Link Prediction (2nd Approach)

- **Data_Creation_2nd_Approach.ipynb**: This notebook explains the second approach for creating a dataset for link prediction. It involves keeping the most popular node as the source and connecting it to a less popular neighbor node.

- **Link_Prediction_of_2nd_Approach.ipynb**: This notebook explores link prediction using the dataset created using the 2nd approach and evaluates the performance of ANN and Logistic Regression models.

## Section 4: Data Creation and Link Prediction (3rd Approach)

- **Data_Creation_3rd_Approach.ipynb**: This notebook explains the third approach for creating a dataset for link prediction. It involves selecting node pairs based on the popularity of nodes, aiming to create a dataset devoid of scale-free network characteristics.

- **Link_Prediction_of_3rd_Approach.ipynb**: This notebook explores link prediction using the dataset created using the 3rd approach and evaluates the performance of ANN and Logistic Regression models.

## General Conclusion

The general conclusion summarizes the key findings and insights from the different approaches, emphasizing the importance of disparities in preferential attachment distributions for accurate link prediction.

## Conclusion

This project provides a comprehensive exploration of temporal network analysis and link prediction strategies, highlighting the significance of preferential attachment in link prediction. The findings guide further exploration and model refinement in network analysis and link prediction.

For detailed descriptions of how each dataset was created in the respective sections, please refer to the corresponding Jupyter Notebooks.
