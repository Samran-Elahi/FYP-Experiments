# FYP-Experiments
This repository contains a list of experiment and approaches that we performed for our Research in my undergraduate final year project.  

# Our Intention 
we wanted to create a way to increase model diversity between neural nets in an ensemble. By increasing model diversity
we hoped that it would lead to reduction in overfitting and cause a regularizing effect. We developed multiple apporaches and this 
repo contains all the appoarches we tried.

# Bas_exp 3
We wanted to find those features that perform poorly on model1 so that we may train them another model. 
We thought by separating the data that performs poorly on model1 and training it on another model would 
increase model diversity in the ensemble and hence would lead to reduction in overfitting. we developed a 
Threshold on the basis of class activation to find the example that performed poorly.

# Bas_exp 5
it is just and extension of Bas_exp 3. 

# Dataset.py
Contains our Data sets and loads them into other experiments.

# Let_us_C
We developed a regularizer and incoperated it into the loss function to create model diversity but it did not reduce overfitting.
