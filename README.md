# MACHINE LEARNING PROJECT FRAMEWORK
`by Nathan Lauga`
*****

**[BUILD IN PROGRESS - January, 10th 2020]**

This repository main goal is to provide a template when starting a Machine Learning project. It allows Data Scientist to have a better understanding of his project and it also help future developers to get a good sense about the project life.

Each directory has a main goal so that you'll be able to retrieve what you wanted to do. 

Here the key is to **create code human readable and not to long**, so try to create a notebook for a specific function (in the end you do as you wish each developer has his own habbits ;) ).

**If you want to get some example about how to use this solution please refer to this repository : [NOT AVAIBLE FOR THE MOMENT] [Machine Learning project structure - Example](#).**

## RECOMMENDED PROJECT PIPELINE WITH THIS FRAMEWORK

With this framework I recommend you to use following this logic :

1. `00_start` : Start the project, by completing `Machine Learning Canvas` document. You can add any other external documents that can be usefull for the project.
2. `01_collect` : Once your project started with all the information you need, data collection should be here : the code that you used should be here but the collected data should be in `_data` (if you only download a csv, just set the details into the folder)
3. `02_quality` : 
4. `03_analyse` : Analyse your raw data, what's in it ? What are the correlations ? etc.
5. `03_preparation` : Transform your data so that the model will be able to use it. Improve your data with feature engineering.
6. `03_analyse` [OPTIONAL] : Analyse your new features if you have some
7. `05_modeling` : Create your model (try different parameters, model types, etc.)
8. `06_validation` : Test your model, it's important to save information about the score like saving a png file of the confusion matrix 
9. `05_modeling` : While the model is not validate, improve the model
10. `07_deployment` : In this section specify how you'll plan to deploy the model. If you're using some code like a Python webapp : refer source code.
11. `08_monitoring` : Precise how the monitoring of the model will be made. You can setup a graphic application here.

## HOW TO START A PROJECT

First clone or download this repo to start from scratch : 
```
git clone https://github.com/Nathanlauga/machine-learning-project-framework
```

When you start a project be sure that you understand his context (who needs this AI, what do you need to do, why you need to do it, etc.) and start to think about what data you'll need to collect.

So what you need before even write a single line of code, please use the Machine Learning Canvas on the `00-START` directory. You can find different format, choose the format that suits you. For more information about this document, you'll find details on its original source : [Machine Learning Canvas -- Louis DORARD](https://www.louisdorard.com/machine-learning-canvas).

## WHAT CAN YOU FIND INTO EACH DIRECTORY ?

### 

*****
Thanks for reading.
Nathan.