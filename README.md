Project Description

This project aims to classify web pages into two categories: evergreen (timeless content) and ephemeral (short-lived content). This distinction is crucial for recommendation systems like StumbleUpon, which aims to provide relevant, long-lasting content suggestions to users. The goal is to predict whether a webpage is evergreen or ephemeral based on its features and metadata.

The project involves data extraction, transformation, and analysis to build a robust classification model that outperforms a baseline approach.

Classification Models:

    Random Forest Classifier:
        An ensemble method based on decision trees, which captures complex relationships in the data.
        Chosen for its robustness and ability to handle both numerical and categorical data.
    Logistic Regression with Cross-Validation:
        A simple linear model used as a baseline comparison.
        Provides easy interpretability and quick performance estimation.
    Dummy Classifier:
        A naive baseline model that uses simple strategies like predicting the majority class.
        Helps evaluate the value added by more sophisticated models.

Model Evaluation:

    Classification Report: Includes metrics like precision, recall, F1-score, and accuracy.
    Comparison of the performance between the advanced models and the baseline model.
