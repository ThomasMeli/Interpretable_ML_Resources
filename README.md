# Interpretable_ML_Resources

This repository is devoted to curating and organizing resources used to increase the ability of humans to understand and explain models. 

It prioritizes quality over quantity, limiting each subsection to the top 5-10 links we've found so far.  It thus doesn't try to be exhaustive.  

The organization of the resources below mostly follows the organization of the exceptional work **Interpretable Machine Learning** by Serg Masís.

# Key concepts of Interpretability:

### Explainability vs. Interpretability vs. Causality

Explainability and interpretability are often conflated as if they are the same thing, so let's take a moment to distinguish them.  Saying a model is **interpretable** is saying that we are capable of _making sense of it_ while saying a model is **explainable** is saying we _understand in an under-the-hood sense of why it is making the predictions it is making_.  I can interpret your behavior if I can make sense of it, but I may not be able to really explain it.  However, when I am really baffled, I can't even interpret your behavior because perhaps it is too complicated.

When it is feasible (and it may not always be), I also strongly recommend **designing experiments** to test particular hypotheses and corroborate or disconfirm what our model interpretations may be saying.  Causal inference and experimental design therefore places an increased focus on the _reality_ of the situation rather than trying to understand what the _model_ is doing.  

## The Predictive Accuracy and Interpretability Trade-off

Models that are more complex can achieve higher predictions when they can make use of potential information in your dataset which is **non-linear** (an increase in one variable has a changing effect on the output variable - density dependence), **non-monotonic** (an increase in one variable doesn't always create an increase or decrease in the output), and can account for **interactions** (when predictor variables are not independent from one another).

## Global vs Local Interpretations

* ..

# General XAI Packages

## XAI Dashboards and Suites in Python

* InterpretML - https://github.com/interpretml/interpret
* Explainer Dashboard - https://github.com/oegedijk/explainerdashboard
* Alibi - https://github.com/SeldonIO/alibi
* AI Explainability 360 - https://github.com/Trusted-AI/AIX360

### Specific XAI Packages
* DiCE - Diverse Counterfactual Explanations - https://github.com/interpretml/DiCE
* Shapash - A Shapley Explainer Dashboard - https://shapash.readthedocs.io/en/latest/

## XAI Packages in R
* https://github.com/ModelOriented/DrWhy
* 

# White Box Models (Traditionally Explainable Models)

### Linear Models 
* **Statsmodels** - Great statistical output for regression models -  https://www.statsmodels.org/stable/index.html


### Sparse Models and Regularization:

Sparse models tend to be more interpretable and explainable because they reduce the complexity of models.
**Sparsity and Regularization** - 

### RuleFit

_"RuleFit is one model-class family that is a hybrid between a LASSO linear regression to get regularized coefficients for every feature and merges this with decision rules, which it also uses LASSO to regularize. These decision rules are extracted by traversing a decision tree finding interaction effects between features and assigning coefficients to them based on their impact on the model. The implementation used in this chapter uses gradient boosted decision trees to perform this task."_ - Serg Masís, Interpretable Machine Learning, pg 115


* **iModel** - https://github.com/csinva/imodels -  "Python package for concise, transparent, and accurate predictive modeling. All sklearn-compatible and easy to use."


# Glass Box Models (Newer Explainable Models)

## Explainable Tree Models

# Model Agnostic Tools

# Black Box Model Explainability

## Explainable Deep Learning Models

* **Tensorboard What-if Tool** - https://www.tensorflow.org/tensorboard/what_if_tool - "The What-If Tool (WIT) provides an easy-to-use interface for expanding understanding of black-box classification and regression ML models. With the plugin, you can perform inference on a large set of examples and immediately visualize the results in a variety of ways. Additionally, examples can be edited manually or programmatically and re-run through the model in order to see the results of the changes. It contains tooling for investigating model performance and fairness over subsets of a dataset."


### NLP Explainability
* **LIT - Language Interpretability Tool** - https://github.com/pair-code/lit - "LIT is built to answer questions such as: What kind of examples does my model perform poorly on?
Why did my model make this prediction? Can this prediction be attributed to adversarial behavior, or to undesirable priors in the training set?  Does my model behave consistently if I change things like textual style, verb tense, or pronoun gender?"

# Interpretable Causal Inference + Counterfactuals

# Feature Selection and Interpretability

# Books

* **Interpretable Machine Learning** - Serg Masís
* **XAI Stories** - Free Online Book - https://pbiecek.github.io/xai_stories/

# Other Aggregations of ML Interpretability Resources

* **H2o AI** https://github.com/h2oai/mli-resources
* "Interesting Resources" - Very nice article summaries https://github.com/pbiecek/xai_resources
* **Awesome-Xai** - https://github.com/altamiracorp/awesome-xai
* **Another Awesome XAI Mostly Papers** - https://github.com/lopusz/awesome-interpretable-machine-learning
* https://github.com/pbiecek/xai_resources
* **Yet Another awesome XAI - Alphabetical Order** - https://github.com/jphall663/awesome-machine-learning-interpretability
