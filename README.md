<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=AntonioLaurance.Titanic_Survival_Predictor" />

# <font align='center'>Machine Learning for Disaster</font>
**Team's name:** *AI's Daemons*\
**Team's members:** 
- Cristobal Eleazar Meza
- Ricardo Campos Luna
- Diego Esteban Zepeda Ceballos


## Summary
**Problem type:** Classification\
**Target class:** Survival

Our proposal to predict the survival rate of a Titanic passenger with given attributes was to analyze all data given from the Kaggle dataset for training 
(you can find it in the **Datasets** directory) to find out the most relevant variables to determine the likelihood of survival of a given passenger, 
after obtaining the most relevant variables, we developed several machine learning models to choose the three models with highest **accuracy** 
and **F1-Score**. 

We geatest problem that we encountered meanwhile we delevoped the ML models was to **tune hyperparameters** for each model proposed this is because it takes many time and other problem that we encountered was that not all models accept **categorical data** during the training process therefore we do **data encoding**. 

**Objetive:** \
Develop a Machine Learning model that can predict with 80% Accuracy the survival rate of a given Titanic passenger.

**Hypothesis:** \
Being a female-child should be the main cause of survival.

## Selected models
- Support Vector Machine (SVM) with RBF kernel
- Logistic Regression
- Neural Networks (Tensorflow model) + SVM

## Links to Colab Notebooks
Link to Colab code (sklearn, seaborn): https://colab.research.google.com/drive/1dw1N9s9WjRrH1vGJHGWhnFHBUhR9ru_r#scrollTo=6Nt8oqEfGk2w

Link to Colab code (pyspark): \
https://colab.research.google.com/drive/1tcXhnANM2wAJf4RnpXOUAyy1fdKaZUKL?usp=sharing
