# Weight & Bias practice using IRIS dataset.

This repository contains code for exploring and analyzing the Iris dataset using Wandb for logging and visualization.

Project Overview
This project investigates the Iris dataset, a classic dataset for classification tasks.
We train multiple machine learning models and compare their performance
We leverage Wandb to log metrics, hyperparameters, and visualizations.

Code Breakdown
1. Data Exploration and Preprocessing:

    The code imports the Iris dataset and converts it into Pandas DataFrames.
    It splits the data into training and testing sets and logs the data table to Wandb.
2. Model Training and Evaluation:

The code defines three functions for different tasks:
    main(name_model, model): Trains a specific model, logs metrics, and visualizes classification plots.
    cross_validation(model): Performs Stratified KFold cross-validation and reports average accuracy, f1_macro, and negative log-loss.
    train_test(model): Splits data, trains a model, and logs metrics to Wandb.
    The code trains and evaluates several models, including Logistic Regression, Linear Discriminant Analysis, K-Nearest Neighbors, Decision Tree, and Gaussian Naive Bayes.
    It logs accuracy, f1_macro, and negative log-loss for each model using Wandb.

3. Visualizations:

    The code utilizes Wandb's sklearn.plot_classifier function to visualize decision boundaries, confusion matrices, and ROC curves for each model.
4. Usage Instructions:

    To run the code, install Wandb and execute the Python script.
    The code will automatically log all results and visualizations to your Wandb project.
   
6. Results and Conclusion:

    The code demonstrates the potential of using Wandb to track and compare different model performances.
    Users can explore the visualized results on their Wandb dashboard for further analysis.
6. Dependencies:
  - Wandb
  - sklearn
  - pandas
7. Contributing:

Feel free to fork this repository and contribute your own code or analysis.
We encourage open discussion and collaboration on improving this project.
