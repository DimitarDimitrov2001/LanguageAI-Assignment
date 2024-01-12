# LanguageAI-Assignment

# Introduction
Welcome to our Language and AI project repository! This project is centered around the use of Natural Language Processing (NLP) techniques to analyze Reddit posts and profile authors into Myers-Briggs Type Indicator (MBTI) personalities. By employing machine learning models such as logistic regression, neural networks with BERT embeddings, and zero-shot DeBERTa models, the team aims to explore and compare their efficacy in accurately classifying MBTI personality types based on textual content. This project is an extension of existing studies, testing additional models and contributing to the broader understanding of digital personality representation.


# How to run the files
1. First, the requirements need to be installed from the Requirements.txt file.
2. Whenever there is no library installed from requirements for some reason, go to Terminal and pip install it manually.

3. Order of running (after 3 the order does not matter): 
    1. `EDA.ipynb`: Exploring the dataset and cleaning dataset. also used to create training and test data. 
    2. `Test.ipynb`:
    3. `preprocessing.ipynb`: This notebook was used to create csvs that contained preprocessed posts and bert_embeddins after undersampling.
    4. `Wordclouds.ipynb`: This notebook produces wordcloud plots for a selected dichotomy.
    5. `Zeroshot.ipynb`: This notebook is used to run the analysis on the test preprocessed data through DeBERTa.
    6. `bert.ipynb`: This notebook was used to create functions such as preprocess_text and get_bert_embeddings. furthermore, neural network model was created, its parameters were tuned and the model evaluation was also done here.
    7. `logistic_reg.ipynb`: This notebook experimented with logistic regression model. 
    9. `baseline_model.ipynb`: This notebook was to create the baseline model and to test its accuracy.
