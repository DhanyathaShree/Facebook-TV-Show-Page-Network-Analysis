# Facebook TV Shows Network Analysis  

## **Abstract**  
This project leverages a large dataset of Facebook pages and their interactions (likes) from November 2017. Representing this data as a network, with **3,892 nodes** (Facebook pages) and **17,262 edges** (mutual likes), the study aims to analyze the structure, key nodes, and communities within the network. By applying graph analysis techniques and machine learning models, insights into viewer engagement levels and information flow are extracted. A **Graph Convolutional Network (GCN)** was implemented for advanced analysis and predictions leveraging graph structure.  

## **Dataset Overview**  
- **Type:** Graph  
- **Nodes:** 3,892 (Facebook pages for TV shows)  
- **Edges:** 17,262 (mutual "likes" between pages)  
- **Maximum Degree:** 126  
- **Minimum Degree:** 1  
- **Average Degree:** 8  

### **Description**  
- **Nodes:** Each node represents a unique Facebook page.  
- **Edges:** An undirected edge connects two pages with mutual likes, indicating potential bi-directional influence.  
- **Categories:** The dataset contains eight distinct types of pages, focusing on TV shows.  

## **Objective**  
The primary goals of this project are:  
1. To analyze the **network structure** of Facebook TV show pages.  
2. To identify **influential nodes** and communities.  
3. To predict **viewer engagement levels** using network connections.  
4. To extract actionable insights for optimizing audience engagement and improving content distribution strategies.  

## **Insights**  
1. **Network Structure:** Key characteristics such as density, transitivity, and degree distribution.  
2. **Influential Nodes:** Identification of central nodes driving the network.  
3. **Community Detection:** Understanding clusters or communities in the network.  
4. **Misinformation Analysis:** Studying the risk of echo chambers and misinformation spread.  
5. **Genre Preferences:** Uncovering patterns in TV show preferences based on mutual likes.  
6. **Comparative Analysis:** Insights into trends across TV show categories.  
7. **Predictive Insights:** Popularity trends and engagement level predictions.  
8. **Applications:** Detecting misinformation, improving content strategies, and mitigating echo chambers.  

## **Technologies Used**  
- **Graph Analysis Libraries:** NetworkX, Matplotlib, Seaborn  
- **Machine Learning Models:** Graph Convolutional Network (GCN), centrality-based analysis  
- **Visualization Tools:** Force-directed layouts, adjacency heatmaps  

## **Key Observations**  
- The network exhibits high variability in node connectivity, with some pages having significantly more mutual likes (degree = 126) than others.  
- Community structures indicate shared audience preferences among TV show genres.  
- Analysis highlights the potential of this network in understanding information dissemination and audience behavior on social media platforms.  

## **Visualization**  
Visualizations include:  
1. Force-directed graph layouts for structural overview.  
2. Degree distributions and adjacency heatmaps for understanding connectivity patterns.  
3. Community clusters highlighting influential groups.  

## **How to Use**  
1. **Data Preprocessing:** Load and preprocess the dataset from the `data` folder.  
2. **Graph Analysis:** Use the provided scripts for community detection, centrality analysis, and degree distributions.  
3. **GCN Model:** Run the GCN implementation for predicting engagement levels.  
4. **Visualizations:** Use Jupyter Notebooks or Python scripts for generating visualizations.  

## **Potential Applications**  
- Optimizing content creation and distribution strategies for marketers.  
- Detecting and addressing misinformation spread.  
- Understanding genre preferences for advertisers.  
- Enhancing engagement strategies for TV show networks.  
