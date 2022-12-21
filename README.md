# Semantic-Relation-Classifier

Project Description<br/>
In this project, I have designed and implemented a semantic relation classifier. A semantic relation is a relation between meanings. For example, let us consider the sentence, "A factory manufactures shoes." In this sentence, "shoes" is the product, and "factory" is the producer. Hence, the semantic relation present in this sentence is Product-Producer.
<br/>As part of this project, the data samples were classified into 4 relations: Cause-Effect, Component-Whole, Product-Producer and Other-Relation.

Tech stack
1. Python - The project is coded in Python
2. Google Colab - Google Colab was used to run the project

Implementation steps
1. The data was preprocessed
2. A SVM model was trained
3. The model was tuned to find the best parameters using GridSearchCV
4. The model was tested against the testing data

Steps to run the project
1. Download the SemanticRelationClassifier.ipynb file
2. Download the dataset.zip file
3. Use Google Colab to run the .ipynb file, upload the dataset.zip file to session storage

Observations
1. The model achieved a test accuracy of 68%.

Conclusion
<br/>The model could have performed better if context was considered, i.e. by using LSTM.

Resources
<br/>Research paper: https://aclanthology.org/S10-1006/
