# JSC270A4

This is our repository for the final assignment for JSC270. This repository contains all files required for submission, mainly the Report, Colab Notebook, Data and Slides. 

For part 2 of the assignment, we chose to explore sentiment in Twitter data. We study the relationship between subjectivity and polarity. 

# Evaluation Comments

## Q1

- Careful about using the max_features attribute in the CountVectorizer. This restricts your vocabulary. This is fine as a hyperparameter to tune, but the true vocabulary without constraint should be above 50,000. This will affect your accuracies later in the question, but you'll only lose a mark once.
- Note that ROC Curves are designed to measure TP and FP for binary classification. In this case a single ROC curve has no meaning; instead Sklearn will fit multiple pairwise curves and plot them together, or average them.

## Q2

- Why is modelling the relationship between polarity and subjectivity an interesting/useful learning task? A bit more detail needed here.
- Excellent data description. A bit more detail about how Textblob computes these scores should be included.
- Are there any other analyses similar to yours? Did your results correspond to those of other scientists?
- Good exploratory data analysis
- Great model explanation. A bit more information on your spline choices for the GAM would be helpful
- Are there certain types of tweets your model performs poorly on?
- Do your results hold when using different hyperparameter settings?
- Good job fitting a series of models to establish a baseline
- Is there anything else you would do if you had more time/data?
- Great work

