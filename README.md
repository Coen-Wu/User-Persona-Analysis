# User Persona Analysis: Decoding Hidden Movie Tastes with NMF & Clustering

This project analyzes user movie-watching preferences using collaborative filtering and unsupervised learning techniques.

# Key Implementation

The project deconstructs the MovieLens Latest Small Dataset to identify latent user personas through three primary stages:

Feature Extraction: Applying Non-negative Matrix Factorization (NMF) to decompose ratings into 6 latent "Content Genes".

User Clustering: Segmenting users into 4 distinct groups using K-Means. 

Visualization (PCA): Using Principal Component Analysis (PCA) to map complex, 6-dimensional user tastes into a 2D "User Segmentation Map" for intuitive analysis. 

# Results & Insights

1. User Segmentation Map

This plot is the core result of dimensionality reduction with PCA, mapping complex 6D user tastes onto a 2D "Market Map." It reveals how different personas are distributed based on their "Market Popularity Dimension" (PC1) and "Movie Style Spectrum" (PC2) scores. 

![User Segmentation Map](./segmentation_map.png)

2. Comprehensive Analysis For a deep dive into the mathematical deconstruction of the 6 Hidden Content Genes (e.g., Modern CGI, 80s Sci-Fi) and detailed cluster-level summaries, please refer to the full Project Presentation (PDF). 



# Techniques Used

Matrix Factorization (NMF)

K-Means Clustering

Principal Component Analysis (PCA)

Data visualization with Matplotlib & Seaborn


Interpretable latent movie preference features

User segmentation map in 2D taste space

Cluster-level summaries of dominant user motivations

# Libraries

pandas, numpy, scikit-learn, matplotlib, seaborn

This project demonstrates how unsupervised learning can be used to discover hidden user personas from rating data.

# Project Structure
