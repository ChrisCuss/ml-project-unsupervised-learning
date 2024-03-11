# Machine Learning Project: Unsupervised Learning

## Overview
This project applies unsupervised learning techniques to the "Wholesale Data" dataset, focusing on exploring and clustering data related to grocery store product sales. The main goal is to uncover insights from the data and communicate these findings to stakeholders through effective data visualization.

## Project Description
The dataset includes details about annual spending on various products by different clients of a wholesale distributor. Through this project, we aim to:

- Perform exploratory data analysis (EDA) and preprocessing to understand the dataset.
- Implement KMeans and hierarchical clustering to identify distinct groups within the data.
- Apply Principal Component Analysis (PCA) to reduce dimensionality and highlight significant features.
- Communicate insights and findings using data visualization techniques.

### Key Outcomes
- **Unsupervised Learning:** Applied KMeans clustering, hierarchical clustering, and PCA to analyze the wholesale data.
- **Data Visualization:** Utilized various visualization tools to communicate insights and patterns discovered in the dataset.
- **Insightful Findings:** Identified distinct customer profiles, such as Coffee Shops, Grocery Stores, Restaurants, and Big Box Stores, each with unique purchasing habits.

## Project Structure
### Part I: EDA and Pre-processing
- **Data Import:** Loaded the dataset for analysis.
- **Data Cleaning:** Addressed missing values and incorrect data.
- **Data Description:** Generated summary statistics for the dataset.
- **Data Visualization:** Created visualizations to explore relationships between variables.
- **Outlier Detection:** Identified and handled outliers in the dataset.
- **Correlation Analysis:** Examined correlations between different variables.
- **Data Transformation:** Standardized the data for clustering analysis.
- **Feature Selection:** Identified key features contributing to customer segmentation.

### Part II: KMeans Clustering
Explored customer segmentation through KMeans clustering, determining the optimal number of clusters and analyzing the characteristics of each cluster.

### Part III: Hierarchical Clustering
Implemented hierarchical clustering to further understand customer groupings and derived insights using dendrogram analysis.

### Part IV: PCA
Applied PCA to identify the most significant combinations of features that best describe customer purchasing behavior.

### Part V: Conclusion
Summarized the key findings from the analysis, highlighting different types of customers, factors distinguishing customer groups, and the influence of location and purchasing methods on buying habits.

### Part VI: Data Visualization
Employed data visualization techniques throughout the project to illustrate the insights gained from the analysis and to support decision-making for stakeholders.

## Insights and Business Implications
- Identified distinct customer profiles with unique purchasing habits, providing a basis for targeted marketing and inventory management.
- Highlighted the importance of product categories like "Milk," "Groceries," and "Detergents_Paper" in customer segmentation.
- Revealed the impact of geographical regions and distribution channels on purchasing patterns.
- Offered actionable insights for the distributor to optimize operations, improve customer satisfaction, and enhance business efficiency.

## Dataset Description
The dataset includes the following columns:
- **FRESH**: Annual spending on fresh products.
- **MILK**: Annual spending on milk products.
- **GROCERY**: Annual spending on grocery products.
- **FROZEN**: Annual spending on frozen products.
- **DETERGENTS_PAPER**: Annual spending on detergents and paper products.
- **DELICATESSEN**: Annual spending on delicatessen products.
- **CHANNEL**: Sales channel (Horeca or Retail).
- **REGION**: Geographical region (Lisbon, Oporto, or Other).