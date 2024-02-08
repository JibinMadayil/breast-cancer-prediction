# breast-cancer-prediction
Breast Cancer Classification project using machine learning algorithms to predict tumor malignancy. The project includes data preprocessing, model training, and evaluation using logistic regression, decision trees, and random forests. Explore the classification performance and contribute to advancing breast cancer diagnosis.


# Breast Cancer Classification

This project aims to classify breast cancer tumors as either malignant or benign using machine learning algorithms. The dataset used in this project contains various features extracted from digitized images of breast cancer biopsies.

## Dataset

The dataset used in this project is `breast-cancer.csv`, which contains the following columns:

- `id`: Unique identifier for each biopsy
- `diagnosis`: The diagnosis of breast tissues (M = malignant, B = benign)
- Other features extracted from the images such as mean radius, mean texture, mean perimeter, etc.

## Data Preprocessing

- The dataset is loaded using pandas.
- Missing values are checked and handled if any.
- The target variable (`diagnosis`) is encoded using LabelEncoder.
- Correlation of each numeric feature with the target variable is calculated and plotted.

## Model Building

Three classification algorithms are trained on the dataset:

1. Logistic Regression
2. Decision Tree
3. Random Forest

The dataset is split into training and test sets, then feature scaling is applied using StandardScaler. Each model's accuracy is evaluated on the training set.

## Evaluation

Each model is evaluated on the test set using the following metrics:

- Precision
- Recall
- F1-score
- Accuracy

## Results

The performance metrics for each model on the test set are as follows:

- Logistic Regression:
  - Accuracy: 95.61%

- Decision Tree:
  - Accuracy: 92.11%

- Random Forest:
  - Accuracy: 94.74%


