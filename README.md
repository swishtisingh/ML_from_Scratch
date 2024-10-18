<!DOCTYPE html>
<html lang="en">

<!DOCTYPE html>
<html lang="en">

<body>
    <div>
        <img src="https://media.licdn.com/dms/image/D5612AQGAyRAx0YfK_A/article-cover_image-shrink_720_1280/0/1713937068564?e=2147483647&v=beta&t=X7-5Z7VcciDdo2uRuaPmeVOd-Bxi5iZHYEFjvw1fxVE" alt="Banner Image" class="banner">
    </div>
</body>

# ML_from_Scratch

> Machine Learning algorithm implementations from scratch using only NumPy.<br>
> This project focuses on implementing popular machine learning algorithms from the ground up, without relying on external libraries like Scikit-learn for the core implementations.

## Table of contents

- [Overview](#overview)
- [Implemented Algorithms](#implemented_algorithms)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code_structure)
- [Examples](#examples)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)

## Overview

This project provides in-depth implementations of widely used machine learning algorithms written in pure NumPy. It serves as an educational resource for understanding the internal workings of these algorithms by implementing them from scratch. The goal is to help users:

- Gain a better understanding of how each machine learning algorithm works.
- Learn the core mathematics and logic behind each algorithm.
- Explore each algorithm’s implementation without relying on external machine learning libraries for the core computation.

## Implemented_Algorithms

The following algorithms have been implemented from scratch using **NumPy**:

### Supervised Learning Algorithms:

- **K-Nearest Neighbors (KNN):** A simple, yet effective classification algorithm that assigns labels based on majority voting of nearest neighbors.
  
- **Linear Regression:** A regression model to predict a continuous output by learning a linear relationship between input features and target variables.
  
- **Logistic Regression:** A binary classification algorithm that models the probability of class membership using a logistic function.
  
- **Naive Bayes:** A probabilistic classifier based on applying Bayes’ theorem with strong (naive) independence assumptions between features.
  
- **Perceptron:** One of the simplest types of artificial neural networks, used for binary classification tasks.
  
- **Support Vector Machines (SVM):** A classification algorithm that finds the optimal hyperplane separating different classes in the feature space.

### Ensemble Methods:

- **Decision Tree:** A non-parametric supervised learning method used for classification and regression tasks by splitting the data recursively based on feature thresholds.
  
- **Random Forest:** An ensemble method that creates multiple decision trees and aggregates their predictions for improved accuracy and robustness.
  
- **AdaBoost:** A boosting algorithm that builds strong classifiers by combining multiple weak classifiers sequentially.

### Unsupervised Learning Algorithms:

- **Principal Component Analysis (PCA):** A dimensionality reduction technique that projects high-dimensional data into lower dimensions while retaining most of the variance.
  
- **K-Means Clustering:** An iterative clustering algorithm that partitions data points into K clusters by minimizing the sum of squared distances within each cluster.

### Dimensionality Reduction:

- **Linear Discriminant Analysis (LDA):** A dimensionality reduction technique used to project data into a lower-dimensional space by maximizing class separability.
  
### Dependencies

This project only uses **NumPy** for implementing the machine learning algorithms from scratch. Other libraries such as **Scikit-learn, Pandas,** and **Matplotlib** are used only for:

- **Data generation:** Generating datasets for testing the implemented algorithms.
  
- **Evaluation:** Comparing the results of our implementations against Scikit-learn’s implementations.
  
- **Visualization:** Plotting decision boundaries and clustering results.

### Core Libraries:

- `numpy`: Required for implementing the algorithms.

### Additional Libraries:

- `scikit-learn`: For generating datasets and comparing performance.
- `matplotlib`: For plotting graphs and visualizations.
- `pandas`: For loading datasets in some cases.

## Installation

To install the dependencies and get started, follow these steps:

1. Clone this repository:
```bash
git clone https://github.com/yourusername/ml-from-scratch.git
cd ml-from-scratch
```

2. Install the required dependencies using the following command:
   
**For Linux or macOS:**
```bash
pip3 install -r requirements.txt
```

**For Windows:**
```bash
pip install -r requirements.txt
```

## Usage

### Running Algorithms
You can run the implemented algorithms using the following command:

```bash
python -m mlfromscratch.<algorithm-file>
```
Where '<algorithm-file>' is the name of the algorithm file without the '.py' extension. For example, if you want to run the Linear Regression algorithm, you can do:

```bash
python -m mlfromscratch.linear_regression
```

## Code_Structure

The project has the following structure:

```arduino

├── mlfromscratch/
│   ├── knn.py
│   ├── linear_regression.py
│   ├── logistic_regression.py
│   ├── naive_bayes.py
│   ├── perceptron.py
│   ├── svm.py
│   ├── decision_tree.py
│   ├── random_forest.py
│   ├── pca.py
│   ├── kmeans.py
│   ├── adaboost.py
│   ├── lda.py
├── data/
│   └── datasets (optional datasets used in testing)
├── requirements.txt
├── README.md
└── .gitignore
```

Each file in the `mlfromscratch/` directory corresponds to a specific machine learning algorithm, implemented entirely using **NumPy**.

## Examples

Below are some examples of how you can run different algorithms implemented in this project:

1. K-Nearest Neighbors (KNN):
```bash
python -m mlfromscratch.knn
```

2. Support Vector Machines (SVM):
```bash
python -m mlfromscratch.svm
```

3. Principal Component Analysis (PCA):
```bash
python -m mlfromscratch.pca
```

You can visualize the decision boundaries, clusters, or PCA projections by modifying the script to include `Matplotlib` plots.

## Contributing

Contributions to this project are welcome! Whether it’s adding new algorithms, improving existing implementations, or writing better documentation, feel free to open an issue or a pull request.

### Steps to Contribute:

1. Fork the repository.
   
2. Create a new branch for your feature or bug fix:
```bash
git checkout -b feature-name
```

3. Commit your changes:
```bash
git commit -m "Add feature or fix description"
```

4. Push your branch:
```bash
git push origin feature-name
```

5. Open a Pull Request (PR) on GitHub.

## Author
### Srishti Singh
Data Scientist and Machine Learning Enthusiast.<br>
Feel free to connect with me on [LinkedIn.](https://www.linkedin.com/in/srishti-singh-921aa52aa/)

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

### Happy Coding!
