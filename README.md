# Graph-Based-Recommendation-System-in-Python
## Problem Statement
Flipkart is one of the largest eCommerce platforms with millions of products listed, 100M+ downloads, and millions of daily active users (DAU). 
To improve user experience with personalization, platform diversity, and boost sales a state-of-the-art recommendation system is much needed.

## Liner(Goal): Build a recommendation system for an eCommerce platform. 
Business Objective
- Improve user experience with personalization
- Improve platform diversity and discovery of long-tail products


# Project Overview

## Business Objective:

There are hundreds of eCommerce websites with millions of products listed.
Personalizing the content is much needed to engage the user with the platform. This is
where recommendation systems come into the picture.
I build a recommendation system using Graph-based learning for an
eCommerce platform.

# Aim:

To build a Graph based recommender system that will recommend the best product for
the users in e-commerce platforms depending on their purchase and search history

# Data Overview :

The dataset contains user information over 9 attributes for an eCommerce website

Tech Stack:
- Language: Python
- Packages: DuckDB, pandas, Numpy
- File Management: Parquet
- Database Management: SQL, SQL querying

# Approach:
1. Understand the problem statement
2. Deepwalk and Node2vec Model training
- Import the necessary packages and libraries
- Read the selected graph
- Save the graph in .edg format
- Graph random walk generation
- Model Building with Word2Vec and Node2Vec
- Save the embeddings in parquet format
3. Result analysis and Visualization
- Import the necessary packages and libraries
- Read the data
- Define a function for generating levels of category
- Use UMAP (Uniform Manifold Approximation and Projection) method as a
dimension reduction strategy
- Visualize the clusters
4. Embedding vector search
- Import the necessary packages and libraries
- Use FAISS (Facebook AI Similarity Search) for generating
recommendations
