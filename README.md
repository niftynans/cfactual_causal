# cfactual_causal

# Counterfactual Generation for Causal Inference and Model Evaluation

This project aims to explore basic counterfactual generation using the DiCE-ML 
library for multi-class classification
on the Penguin Species dataset and check for the causal
dependencies in factual and counterfactual data.

We used the Palmer Archipelago (Antarctica) penguin dataset.
Data were collected and made available by Dr. Kristen Gorman 
and the Palmer Station, Antarctica LTER, a member of the 
Long Term Ecological Research Network.

The data can be found at: shorturl.at/apvyW


## Libraries Used

We use pandas for database management, cleansing and manipulation 
for various tasks and NumPy for vital numerical computations.

Plotly's Python graphing library makes interactive, publication-quality graphs. 
Seaborn is a Python data visualization library based on 
matplotlib which provides a high-level interface for drawing attractive and 
informative statistical graphics.
Plotly, Matplotlib and Seaborn are used for data visualization.

We used Scikit-learn for basic machine learning modules including classification.
Scikit-learn is a free software machine learning library for the Python 
programming language. It features various classification,
regression and clustering algorithms including support vector machines

DiCE-ML is used for generating counterfactual data.
DiCE is based on recent research that generates CF explanations for any ML model. 
The core idea is to setup finding such explanations as an optimization problem 

CausalNex is a Python library that uses Bayesian Networks to 
combine machine learning and domain expertise for causal reasoning. 
You can use CausalNex to uncover structural relationships in your data, 
learn complex distributions,
and observe the effect of potential interventions.
