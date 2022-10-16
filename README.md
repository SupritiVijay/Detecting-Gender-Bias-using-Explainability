# Detecting-Gender-Bias-using-Explainability

## Abstract: 
Explanations for AI systems have been used to improve the trustworthiness of these systems.
These explanations can be used to find the undesirable implicit biases that machine learning
models can rely on for their outputs. We apply this concept to detect gender bias in sentiment
analysis models for textual data. With the help of an Equity Evaluation Corpus (EEC), we use
different gender signals for otherwise identical input to the system and use explanations from
LIME and SHAP to find a trend of bias, and identify terms that contribute the most to it.

## Motivation:

Consider a set of three sentences fed into the model, only with different gender signals, such as:
* "He was furious," 
* "She was furious," and 
* "They were furious." 

All three of these sentences should ideally predict the same final sentiment polarity. However, since the model learns from the training set, it learns undesirable associations between words which we observe as gender bias. 

Gender bias in language models can be harmful in more than one way, considering their potential impact on downstream tasks which have vast industrial applications.

## Objective: 

Our aim is to: 
* Address whether Explainable AI methods can be used to detect gender bias in textual data.  

* Present the application of model-agnostic methods on the dataset and how these explanations help uncover the hidden bias.

