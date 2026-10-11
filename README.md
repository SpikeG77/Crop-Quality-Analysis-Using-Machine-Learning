# Crop Quality Analysis Using Machine Learning

## Overview

This project explores the use of machine learning to analyze rice kernel features and classify rice quality and variety.

## Objectives

- Extract measurable features from rice kernel images.
- Prepare and preprocess a dataset for machine learning.
- Train and evaluate classification models.
- Compare KNN, SVM, Random Forest, and Extra Trees.
- Evaluate predictions using accuracy scores, confusion matrices, precision, recall, and F1-scores.

## Dataset

The dataset contains extracted rice kernel features from Baskhati and Jeerakati rice samples.

The project uses features obtained from image processing and manually prepared labels.

## Models

- K-Nearest Neighbors (KNN)
- Decision Trees

## Evaluation

The models are evaluated using separate accuracy scores for the quality label and rice variety, along with combined exact-match accuracy and confusion matrices.

Final performance figures will be added after appropriate validation on images not used for training.

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Status

Work in progress. Dataset preparation, feature extraction, and initial classification experiments have been performed. Model comparison, validation, and further improvements are ongoing.

## How to Run

1. Clone or download this repository.
2. Install the dependencies using `pip install -r requirements.txt`.
3. Open the notebook in Jupyter Notebook or VS Code.
4. Run the notebook cells in order.

## Future Improvements

- Improve validation using image-level train/test splits.
- Tune model hyperparameters.
- Improve broken-kernel and chalkiness classification.
- Develop an API and user interface for image-based predictions.
