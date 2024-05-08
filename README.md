# H2OQualitizer : WaterPotability

This project aims to develop machine learning models for predicting the potability of water based on various physicochemical properties. The project is part of a Machine Learning course and utilizes Python and Jupyter Notebook as the primary tools.

## Dataset

The dataset used in this project is obtained from Kaggle: [Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability). It contains water quality measurements from various sources, including wells, municipalities, and surface water bodies. The dataset includes features such as pH, hardness, solids, chloramines, and organic carbon content.

## Preprocessing

The dataset contains outliers and missing values, which are handled using the following techniques:

1. **Missing Value Imputation**: The missing values in the dataset are imputed using the MICE (Multivariate Imputation by Chained Equations) method.
2. **Outlier Removal**: Multivariate outliers are detected and removed using the Minimum Covariance Determinant (MCD) method.

## Models

The project explores various machine learning models for both regression and classification tasks:

1. **Regression Models**: Linear Regression, Ridge Regression, Lasso Regression, and Elastic Net Regression.
2. **Classification Models**: Support Vector Machines (SVM), Decision Trees, K-Nearest Neighbors (KNN), Random Forest Classifier, and Multi-Layer Perceptron (MLP) Classifier.
3. **Clustering Models**: K-Means Clustering and Hierarchical Clustering.

## Results

The classification models achieved the following accuracies:

- Support Vector Classifier (SVC): 66.19%
- Decision Tree Classifier: 62.32%
- K-Nearest Neighbors (KNN): 63.5%
- Random Forest Classifier: 63.6%
- Multi-Layer Perceptron (MLP) Classifier: 66.8%

Among the classification models, the MLP Classifier demonstrated the highest accuracy of 66.8%.

## Usage

To run this project, follow these steps:

1. Clone the repository: `git clone https://github.com/jay-singhvi/H2OQualitizer.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Launch Jupyter Notebook: `jupyter notebook`
4. Open the relevant notebook files and run the cells to preprocess the data, train the models, and evaluate the results.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
