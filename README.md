# Mushroom Classification Using Machine Learning

## Project Overview
This beginner-friendly supervised machine learning project predicts whether a mushroom is labelled edible (`e`) or poisonous (`p`) based on physical characteristics. It compares a Decision Tree classifier with a K-Nearest Neighbors (KNN) classifier.

**Important:** This is an educational exercise only. Never rely on this model to decide whether a real mushroom is safe to eat.

## Dataset
- **Source:** UCI Machine Learning Repository — Mushroom
- **Link:** https://archive.ics.uci.edu/dataset/73/mushroom
- **Dataset size:** 8,124 examples and 22 input features
- **Target:** Edible or poisonous

## Project Contents
- `mushroom_classification.ipynb` — notebook covering data loading, missing-value checks, preprocessing, model training, accuracy comparison, and confusion matrices.

## Setup Instructions
1. Install Python 3.10 or later.
2. Download or clone this repository.
3. (Optional but recommended) Create and activate a virtual environment.
4. Install the required libraries:

   ```bash
   python -m pip install pandas numpy scikit-learn matplotlib seaborn ucimlrepo jupyter
   ```

5. Launch Jupyter:

   ```bash
   jupyter notebook
   ```

6. Open `mushroom_classification.ipynb` and run the cells from top to bottom. Internet access is needed to fetch the dataset from UCI.

## Model Evaluation and Results

Two machine learning classification algorithms were implemented and evaluated on the Mushroom dataset.

| Model | Test Accuracy |
|---|---:|
| Decision Tree Classifier | 100.00% |
| K-Nearest Neighbors (KNN) | 100.00% |

The models were evaluated using accuracy scores and confusion matrices. Accuracy measures the proportion of correctly classified examples, while the confusion matrix provides a more detailed view of correct and incorrect predictions for each class.

### Comparison

Based on the test results, **[insert the better-performing model]** achieved higher accuracy on the test dataset. This comparison helped demonstrate how different machine learning algorithms can perform differently on the same classification problem.

### Conclusion

Through this project, I learned how to prepare a categorical dataset, handle missing values, encode features, train classification models, and evaluate their performance. Comparing Decision Tree and KNN also helped me understand the importance of testing models on unseen data rather than relying only on training performance.

