This repository focuses on supervised learning concepts using ensemble models and evaluates a semi-supervised learning approach.
The dataset is the Pima Indians Diabetes dataset from Kaggle is used. The data is preprocessed to handle missing values and split into training and testing sets.
I used the following Machine Learning Models: a Decision Tree classifier, a Random Forest classifier, a Bagging classifier with an SVM base model and an AdaBoost classifier with a Decision Tree base model

Each model's performance is assessed using precision, recall, F1-score, and a confusion matrix. The differences in model performance are analyzed.

The best-performing classifier is adapted using SelfTrainingClassifier, and its performance is compared to a fully supervised approach.

I used Python, scikit-learn, and data handling libraries.
