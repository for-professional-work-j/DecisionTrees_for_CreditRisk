# DecisionTrees_for_CreditRisk

This aim of this notebook is intended to deepen my understanding of Decision Trees by developing a decision tree based machine learning model for a financial use case.

I was inspired to explore Gradient Boosting further after reading the approach presented in Gradient Boosting for Interpretable Risk Assessment in Finance (Kori & Hugar, 2021). I believe that this paper highlighted the importance of bridging the gap between predictive accuracy and interpretability in financial risk models.

I've attached a link to the paper  in case you're interested in reading it [here](https://www.researchgate.net/profile/Anita-Kori/publication/386052952_Gradient_Boosting_for_Interpretable_Risk_Assessment_in_Finance_A_Study_on_Feature_Importance_and_Model_Explainability/links/674173dd7ca4cb2842a3ef7a/Gradient-Boosting-for-Interpretable-Risk-Assessment-in-Finance-A-Study-on-Feature-Importance-and-Model-Explainability.pdf).

The GitHub ["Machine learning algorithms for predicting default of Credit Card clients" by MatteoM95](https://github.com/MatteoM95/Default-of-Credit-Card-Clients-Dataset-Analisys?tab=readme-ov-file#machine-learning-algorithms-for-predicting-default-of-credit-card-clients-) also served as a basis for me to learn and structure my approach in this notebook - especially with regards to the Data Expoloration stage. I followed this project because I aspire to explain concepts and present analysis as clearly and effectively as MatteoM95 does.

While currently working through Introduction to Machine Learning with Python by Andreas C. Müller and Sarah Guido, I also wanted to reinforce my understanding of decision tree–based models by comparing the performance and interpretability of Gradient Boosting and Random Forest algorithms in a practical context.

Therefore, this notebook will aim to compare Random Forest (RF) and Gradient Boosting (GB) models to predict the likelihood of default on credit card payments. The goal is not only to evaluate which model performs better in terms of accuracy and F1-score, but also to examine their interpretability, generalization behavior, and how each model responds to different data treatments such as SMOTE and PCA.

Any constructive criticism, input on my methods or what can be improved is definitely welcomed as I start my foray into the world of machine learning.

Note : I would advise you to open this in Colab as some outputs did not render properly when I saved a copy of the notebook into GitHub.
