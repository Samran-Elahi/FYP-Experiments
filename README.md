# FYP-Experiments
This repository contains a list of experiment and approaches that we performed for our Research in my undergraduate final year project.  

# Our Intention 
we wanted to create a way to increase model diversity between neural nets in an ensemble. By increasing model diversity
we hoped that it would lead to reduction in overfitting and cause a regularizing effect. We developed multiple apporaches and this 
repo contains all the appoarches we tried.

# Bas_exp 2
We wanted to find those features that perform poorly on model1 so that we may train them another model. 
We thought by separating the data that performs poorly on model1 and training it on another model would 
increase model diversity in the ensemble and hence would lead to reduction in overfitting. we developed a 
Threshold on the basis of class activation to find the example that performed poorly.

# Bas_exp 5
it is just and extension of Bas_exp 2. 

# Dataset.py
Contains our Data sets and loads them into other experiments.

# Let_us_C
We developed a regularizer and incoperated it into the loss function to create model diversity but it did not reduce overfitting.

# With Regualarizer
so thses notebook contains our final experiment where we constructed a regualarizer and incoperated it into the loss function. 
We were successful in achiveing model diversity however accuracy remained unchanged.

# FYP_Report 
This is the formal report we presented to the FYP committe. It contains all the detailed explanation about each experiment and apporach we took in our FYP. We also prepared an online presentation which can be viewed on the following link :
https://drive.google.com/file/d/12K5HZcNJCCCfifi4RmAEYhDzw7G5wtS3/view?usp=sharing


 
