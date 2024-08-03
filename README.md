# stock-market-network-analysis-india
Network Analysis of Indian Stock Market

# Network Analysis of Indian Stock Market

## Overview
This project performs a network analysis of stock price data from the Indian stock market. The objective is to explore the interconnections between different stocks based on their price movements over time, gaining insights into the underlying structure and dynamics of the stock market.

## Introduction
We constructed a network of stocks and analyzed its properties to gain insights into the structure and dynamics of the stock market. This comprehensive network analysis utilized various libraries such as pandas, numpy, matplotlib, seaborn, and networkx to process the data, calculate correlations, and visualize the network.

## Data Collection and Preprocessing
- Collected historical stock price data for various stocks listed on the Indian stock market.
- Data obtained from the National Stock Exchange (NSE) consisting of daily closing prices from 01 Feb, 2021 to 31 Jan, 2022.
- Code processes the data by reading the dataset directory, sorting files, and removing the first file (index).

## Correlation Calculation
- Calculated the correlation matrix between the return prices of different stocks using the Pearson correlation coefficient method.
- Printed the correlation matrix to analyze the linear relationship between the variables.

## Network Analysis
- Constructed an adjacency matrix for different thresholds (0.25, 0.3, 0.5) based on the correlation matrix.
- Generated graphs for different thresholds to visualize the network structure.
- Analyzed centrality measures including Degree Centrality, Closeness Centrality, Betweenness Centrality, and Eigenvector Centrality.
- Examined Degree Distribution, Edge Density, and Local Clustering Coefficient for different thresholds.

## Results
- Centrality measures helped identify influential stocks and their roles within the network.
- Federal Bank exhibited the highest Degree Centrality, Closeness Centrality, and Betweenness Centrality measures at a threshold of 0.5.
- ITC had the highest Betweenness Centrality measure at a threshold of 0.25.

## Conclusion
- Demonstrated the application of network science techniques to analyze financial market data.
- Gained valuable insights into stock market dynamics through network construction and centrality measures analysis.
- Suggested further research in exploring dynamic network properties, community detection, and predictive modeling based on network structure and dynamics.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- networkx
