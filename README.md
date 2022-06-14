# Graph-Based-Recommendation-System-in-Python

# Project Overview

## Business Objective:

There are hundreds of eCommerce websites with millions of products listed.
Personalizing the content is much needed to engage the user with the platform. This is
where recommendation systems come into the picture. You must have heard about
some recommendation systems such as Content-Based, Collaborative filtering, etc. In
recent years Graph, Learning-based Recommendation systems have witnessed fast
development.
This project aims to give you a brief idea about recommendation systems and how they
work. Moreover, I build a recommendation system using Graph-based learning for an
eCommerce platform.

# Aim:

To build a Graph based recommender system that will recommend the best product for
the users in e-commerce platforms depending on their purchase and search history

# Data Overview :

The dataset contains user information over 9 attributes for an eCommerce website
Link to download the data:
https://drive.google.com/file/d/1XfXqenvh2bws8g20sPK4Ti78_M9C0LF-/view?usp=shari
ng
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
