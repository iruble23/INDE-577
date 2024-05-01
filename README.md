# Termite Data Analysis Repository - INDE-577

## Overview

Welcome to the Termite Data Analysis Repository, a comprehensive collection of machine learning analyses focused on predicting termite behavior and wood decomposition based on a global dataset. This repository is organized into subdirectories, each dedicated to a different machine learning algorithm, covering both supervised and unsupervised learning techniques. The primary goal is to explore various machine learning strategies and their applications in ecological data science, particularly in understanding termite behavior as it relates to their roles as decomposers.

## Significance of Termites in Ecological Research

Termites play a crucial role in the ecosystem as decomposers. They break down tough plant fibers, recycling dead and decaying trees into nutrients that enrich the soil, which supports new plant growth and helps regulate the atmosphere's carbon dioxide levels. Understanding their behavior and impacts through data science provides valuable insights into ecosystem dynamics and helps in forest management and conservation strategies.

## Repository Structure

The repository is organized into the following sections, each containing subdirectories for specific machine learning algorithms:

- **Supervised Learning**:
  - [Perceptron](Supervised%20Learning/perceptron/perceptron.ipynb): Implementation of the perceptron algorithm for binary classification of termite discovery.
  - [Logistic Regression](Supervised%20Learning/logistic_regression/logistic_regression.ipynb): Application of logistic regression to predict termite presence.
  - [Linear Regression](Supervised%20Learning/linear_regression/linear_regression.ipynb): Uses linear regression to model the relationship between environmental factors and wood decay.
  - [Gradient Descent](Supervised%20Learning/gradient_descent/gradient_descent.ipynb): Demonstrates the use of gradient descent in optimizing logistic regression models.
  - [Neural Network](Supervised%20Learning/neural_network/neural_network.ipynb): Application of neural networks to understand complex relationships and predict outcomes in termite activity and wood characteristics.
  - [K-Nearest Neighbors](Supervised%20Learning/k_nearest_neighbors/k_nearest_neighbors.ipynb): Utilizes KNN to classify termite discovery based on proximity to known data points.
  - [Decision Tree](Supervised%20Learning/decision_tree/decision_tree.ipynb): Employs decision trees to make predictions and derive decision rules that govern termite behavior.
  - [Ensemble Methods](Supervised%20Learning/ensemble_methods/ensemble_methods.ipynb): Focuses on combining models like Random Forests and Gradient Boosting to improve predictions in termite data analysis.

- **Unsupervised Learning**:
  - [K-Means Clustering](Unsupervised%20Learning/k_means_clustering/k_means_clustering.ipynb): Exploration of k-means clustering to find patterns in termite data.
  - [DBSCAN Clustering](Unsupervised%20Learning/dbscan_clustering/dbscan_clustering.ipynb): Application of DBSCAN to identify natural groupings and outliers within termite data.

Each subdirectory contains:
- A detailed Jupyter notebook with code, visualizations, and explanations.
- A `README.md` file that discusses the specific machine learning algorithm, its application, and insights gained from the analysis.


## Dataset Overview

The dataset used across these analyses includes measurements from various wood blocks exposed to termite habitats around the world, with features such as:
- `initial_wt`: Initial weight of the wood.
- `final_wt`: Final weight after exposure.
- `termite_discovery`: Whether termites were discovered in the wood block.

This data helps us understand not only the factors influencing termite activity but also their impact on wood decomposition rates globally.

## Supervised and Unsupervised Learning in Data Science

This project explores both supervised and unsupervised learning techniques. Supervised learning involves training a machine learning model on a labeled dataset, crucial for tasks such as predicting termite activity. Unsupervised learning, on the other hand, involves finding hidden patterns or intrinsic structures in unlabeled data, useful for discovering natural groupings or anomalies in ecological data.

## How to Navigate and Use This Repository

To make the most of this repository:
1. Clone or download the repository to your local machine.
2. Each subdirectory can be accessed independently with its own datasets and notebooks.
3. Follow the instructions in the README.md files of each subdirectory to run the notebooks.
4. Contributions and feedback are welcome. Please create a pull request or issue if you have suggestions or find bugs.

## Contact Information

- **Name**: Isabelle Ruble
- **Email**: ir23@rice.edu
- **Institution**: Rice University

Feel free to reach out with any questions or if you are interested in contributing to the project.

## References and Further Reading

- [Termite Ecological Role](https://www.sciencedirect.com/science/article/pii/S0960982213000833)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)

Thank you for visiting this repository, and we hope you find the analyses informative and applicable to your work or research!
