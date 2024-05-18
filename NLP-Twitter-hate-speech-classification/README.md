# Dataset
### labeled datasset collected from twitter
# Overview
### This project aims to classify tweets into two categories: those containing hate speech and those without hate speech. The dataset used for this task is collected from Twitter and is labeled with binary classes: 0 for tweets with no hate speech and 1 for tweets containing hate speech. The classification model is evaluated using the macro F1 score, which is suitable for imbalanced datasets like this one.

# After hyperparameter tuning using Optuna, the best hyperparameters found for the classification model are as follows:

### Vectorizer: TF-IDF
### Ngram Range: (1, 1)
### Model: SGDClassifier
### SGDClassifier(alpha=0.0003707384093093721, loss='modified_huber', max_iter=407, penalty='elasticnet', random_state=42)
###  The macro F1 score achieved with these hyperparameters is 0.9607.
