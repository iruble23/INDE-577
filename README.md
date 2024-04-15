# Termite Data Analysis Repository - INDE-577

## Overview

Welcome to the Termite Data Analysis Repository, a comprehensive collection of machine learning analyses focused on predicting termite behavior and wood decomposition based on a global dataset. This repository is organized into subdirectories, each dedicated to a different machine learning algorithm. The primary goal is to explore various supervised learning techniques and their applications in ecological data science, particularly in understanding termite behavior as it relates to their roles as decomposers.

## Significance of Termites in Ecological Research

Termites play a crucial role in the ecosystem as decomposers. They break down tough plant fibers, recycling dead and decaying trees into nutrients that enrich the soil, which supports new plant growth and helps regulate the atmosphere's carbon dioxide levels. Understanding their behavior and impacts through data science provides valuable insights into ecosystem dynamics and helps in forest management and conservation strategies.

## Repository Structure

The repository is organized as follows:
- [Supervised Learning\perceptron\perceptron.ipynb](Perceptron/): Implementation of the perceptron algorithm for binary classification of termite discovery.
- [Supervised Learning\logistic_regression\logistic_regression.ipynb](Logistic_Regression/): Application of logistic regression to predict termite presence.
- [Supervised Learning\linear_regression\linear_regression.ipynb](Linear_Regression/): Uses linear regression to model the relationship between environmental factors and wood decay.
- [Supervised Learning\gradient_descent\gradient_descent.ipynb](Gradient_Descent/): Demonstrates the use of gradient descent in optimizing logistic regression models.
- Additional subdirectories will be added as the project expands to include unsupervised learning techniques and more complex models.

Each subdirectory contains:
- A detailed Jupyter notebook with code, visualizations, and explanations.
- A `README.md` file that discusses the specific machine learning algorithm, its application, and insights gained from the analysis.

## Dataset Overview

The dataset used across these analyses includes measurements from various wood blocks exposed to termite habitats around the world, with features such as:
- `initial_wt`: Initial weight of the wood.
- `final_wt`: Final weight after exposure.
- `termite_discovery`: Whether termites were discovered in the wood block.

This data helps us understand not only the factors influencing termite activity but also their impact on wood decomposition rates globally.

## Supervised Learning in Data Science

Supervised learning involves training a machine learning model on a labeled dataset, which means that each example in the training set is paired with an output label. This project focuses on supervised learning techniques to predict outcomes based on known data points, which is crucial for tasks such as predicting termite activity, an important factor in ecological studies and wood industry management.

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
