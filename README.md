# Unsupervised Learning: Clustering on Raisin Data

Hey there! This is a simple notebook where I dive into clustering techniques using a dataset about raisins. It's all about exploring how different methods group the data without any labels upfront.

## What's Inside?

- **Data Prep**: Loading the raisin CSV, checking for issues, visualizing outliers and distributions, and scaling everything so it's fair game for clustering.
- **KMeans Basics**: Figuring out the best number of clusters with elbow plots, and testing random vs. smarter (KMeans++) starting points.
- ** Evaluations**: Stuff like purity, mutual info, and silhouette scores to see how good the clusters are.
- **Dimensionality Reduction**: Using PCA to simplify the data and t-SNE for some cool visualizations.
- **DBSCAN Adventures**: Trying density-based clustering with Euclidean and Mahalanobis distances, including how to pick the right settings.
- **Comparisons**: Seeing how clustering works on the full data vs. reduced versions, with metrics to back it up.

The dataset has features like area, perimeter, and eccentricity for different raisin types. I used Python libs like pandas, scikit-learn, matplotlib, and seaborn.


