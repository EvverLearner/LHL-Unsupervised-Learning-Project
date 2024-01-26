# machine_learning_project-unsupervised-learning

## Project/Goals
This project is an exercise in unsupervised learning on a dataset about a wholesaler's clients. PCA, Kmeans clustering, and Hierarchical clustering models are used to facilitate an analysis, from which interpretations are made. Appropriate visualization tools are used to communicate the insights gained from the analysis.

## Process
1. Performed EDA on the dataset, including preparing the data for clustering models (ex. scaling).
2. I began with applying PCA first, as I found it difficult to visualize the clustering results without reducing dimensions.
3. Kmean clustering was perfomed next.
4. Hierarchical clusering was performed last.
5. Project concludes with a final viewing of the dataset and interpretations of the results are made.

## Results
Both clustering models were effective at forming fewer clusters than the amount of product types. This implies that some of the current product categories can be combined, if it would be useful for further business or analysis applications. Correlation values were especially high among `Grocery` and `Paper products & Detergents`, followed by `Grocery` and `Milk`.

## Challenges 
1. Understanding the context of the dataset, and what the goal of applying unsupervised models is in this specific case.
2. Learning the application of clustering and PCA, how to implement it into this dataset.

## Future Goals
1. Track the changes to the dataset in a way that still includes original features, like `Region`.
2. Implement hyperparameter tuning methods to further explore and refine the models.
3. Understand the current models more in depth, in order to innovate better models.
