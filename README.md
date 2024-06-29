# Pokémon Clustering Analysis

--- 
## Project Overview
This Pokémon Clustering Analysis project applies k-means clustering to classify Pokémon based on various attributes such as HP, Attack, Speed, and Defense. The analysis aims to identify distinct groups of Pokémon that share similar characteristics, helping players and analysts understand potential strategies and team compositions.

---

## Results
The analysis categorizes Pokémon into three main clusters:

Cluster 1: Lower-tier Pokémon with generally lower stats.
Cluster 2: Offensively oriented Pokémon with high HP and Attack.
Cluster 3: Defensive Pokémon excelling in Speed and Defense.
Each cluster's characteristics can guide players in team building and strategy development.

---

## Libraries
This project requires the following R packages:
- `tidyverse` for data manipulation and visualization
- `tidymodels` for modeling and validation
- `GGally` for extended visualizations
- `plotly` for interactive plots
- `forcats` for factor manipulation

---
## Data
The dataset pokemon.csv should be placed in the data directory of your project. This file contains Pokémon attributes necessary for the clustering analysis.

---

## Scripts
Data Preparation: Load and preprocess the data.
Clustering: Perform k-means clustering to categorize Pokémon.
Visualization: Generate plots to visualize the characteristics of each cluster.
Run the scripts in the provided order to ensure the data flows through the preprocessing steps correctly into the clustering and then to the visualization.

---
