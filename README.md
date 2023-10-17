# Temporal Network Analysis and Link Prediction

This repository contains Jupyter Notebooks for conducting temporal network analysis and link prediction within the network. The project is divided into several sections, each focusing on different approaches and methods for analyzing network dynamics and predicting connections.

## Project Overview

In this project, we explore the temporal dynamics of networks and link prediction. The primary objectives are as follows:

1. **Temporal Network Analysis**: Exploring the dynamics of a network over time, including the calculation of time-aware centrality metrics and identifying common nodes between successive time periods.

2. **Link Prediction**: Creating datasets for link prediction using various approaches and evaluating the performance of different models for predicting connections within the network.

## Section 1: Temporal Network Analysis

- **[Temporal_Network_Analysis.ipynb](Code/Temporal_Network_Analysis.ipynb)**: This Jupyter Notebook explores two types of network analysis on temporal data, focusing on understanding network dynamics over different time periods.

    - Analysis 1: Time-Aware Network Centrality Measures.
    - Analysis 2: Common Nodes Between Successive Time Periods.

## Section 2: Data Creation and Link Prediction (1st Approach)

- **[Data_Creation_1st_Approach.ipynb](Code/Data_Creation_1st_Approach.ipynb)**: This notebook explains the first approach for creating a dataset for link prediction. It involves connecting less popular nodes to neighbors of more popular nodes to create a well-balanced dataset.

- **[Link_Prediction_of_1st_Approach.ipynb](Code/Link_Prediction_of_1st_Approach.ipynb)**: This notebook explores link prediction using the dataset created using the 1st approach and evaluates the performance of Artificial Neural Networks (ANN) and Linear Regression models.

## Section 3: Data Creation and Link Prediction (2nd Approach)

- **[Data_Creation_2nd_Approach.ipynb](Code/Data_Creation_2nd_Approach.ipynb)**: This notebook explains the second approach for creating a dataset for link prediction. It involves keeping the most popular node as the source and connecting it to a less popular neighbor node.

- **[Link_Prediction_of_2nd_Approach.ipynb](Code/Link_Prediction_of_2nd_Approach.ipynb)**: This notebook explores link prediction using the dataset created using the 2nd approach and evaluates the performance of ANN and Logistic Regression models.

## Section 4: Data Creation and Link Prediction (3rd Approach)

- **[Data_Creation_3rd_Approach.ipynb](Code/Data_Creation_3rd_Approach.ipynb)**: This notebook explains the third approach for creating a dataset for link prediction. It involves selecting node pairs based on the popularity of nodes, aiming to create a dataset devoid of scale-free network characteristics.

- **[Link_Prediction_of_3rd_Approach.ipynb](Code/Link_Prediction_of_3rd_Approach.ipynb)**: This notebook explores link prediction using the dataset created using the 3rd approach and evaluates the performance of ANN and Logistic Regression models.

## Conclusion

In our comprehensive exploration of temporal network analysis and link prediction strategies, we have made several noteworthy comparisons and insights. The first approach, emphasizing the distinction in preferential attachment distributions between existing and non-existing edges, resulted in the highest link prediction accuracy, underscoring the importance of this distinction. On the contrary, the third approach, which sought to balance preferential attachment distributions, yielded the lowest performance, indicating the need to highlight differences in preferential attachment. Additionally, our analyses of time-aware network centrality measures and common nodes between successive time periods provided valuable insights into the temporal dynamics of the network. These findings collectively emphasize the significance of training classifiers with data that accentuates disparities in preferential attachment, a crucial property for accurate link prediction, guiding further research and model refinement in the dynamic field of network analysis.