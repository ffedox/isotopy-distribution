# Identifying medical drama narratives: a multi-output regression approach with CNNs and BERT

This repository contains the final project for the 2022-23 edition of the [Natural Language Processing](https://albarron.github.io/teaching/natural-language-processing/) course. The aim of the project was to predict the distribution of three plot types that are characteristic of the medical drama genre. To address this task, three text regression models were trained and compared.

More information about the creation of the corpus can be found [here](https://github.com/TinfFoil/dar_tvseries).

## Contents (as of February 2023)

1. [Regression_Baselines.ipynb](https://github.com/ffedox/nlp/blob/main/Regression_Baselines.ipynb): rule-based, reproducible baselines for evaluating the models with R², MAE and RMSE.
2. [Regression_with_CNNs.ipynb](https://github.com/ffedox/nlp/blob/main/Regression_with_CNNs.ipynb): two CNN models, one with manual tuning and the other optimized automatically using [Keras Tuner](https://keras.io/keras_tuner/).
3. [Regression_with_BERT.ipynb](https://github.com/ffedox/nlp/blob/main/Regression_with_BERT.ipynb): model based on Google's [BERT](https://en.wikipedia.org/wiki/BERT_(language_model)).
4. [NLP_Report.pdf](https://github.com/ffedox/nlp/blob/main/NLP_Report.pdf): written report providing a detailed overview of the models and the obtained results.
