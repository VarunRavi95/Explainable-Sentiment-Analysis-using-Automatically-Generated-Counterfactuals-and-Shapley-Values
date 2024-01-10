# Text_Mining_Project
This is a repository for the Text Mining Project on Explainable Sentiment Analysis using Automatically Generated Counterfactuals and Shapley Values.

The augmented dataset here consists of the original and human generated counterfactuals dataset from Kaushik et.al and automatically generated counterfactuals from Yang et.al. 

Additionally, there is a notebook(Explainable_SentimentAnalysis_Results_Analysis.ipynb) performing analysis on the Robustness and Interpretability of SVM, BERT and ROBERTA using Counterfactuals and the SHAP python package and a HTML file showing the results.

Please note that in order to reproduce the results from the notebook for BERT and RoBERTA, the trainer function needs to be run and the models have to be saved with an appropriate name in order to perform SHAP analysis. The saved models will be saved in the "Models" folder, which is currently empty since saved models could not be uploaded to Github owing to their large size.
