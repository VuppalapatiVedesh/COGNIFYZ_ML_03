Task: Cuisine Classification

Objective:
To build a machine learning classification model that predicts the
primary cuisine of a restaurant based on its attributes.

Dataset:
A shared restaurant dataset containing information such as pricing,
customer votes, ratings, and cuisine types. The dataset is stored
in the Dataset folder and is used across all tasks.

Approach:
- Selected relevant numerical features related to pricing and engagement
- Removed missing values to ensure data consistency
- Simplified cuisine labels by considering only the primary cuisine
- Encoded cuisine categories using Label Encoding
- Trained a Random Forest Classifier for multi-class classification
- Evaluated the model using accuracy, classification report, and confusion matrix
- Visualized class distribution and feature importance

Evaluation:
The Random Forest model achieved reliable performance and trained
efficiently after simplifying cuisine categories.

Conclusion:
This task demonstrates the application of supervised machine learning
for multi-class cuisine classification. Simplifying cuisine labels
improved training efficiency while maintaining meaningful predictions.
