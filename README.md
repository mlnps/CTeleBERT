# CTeleBERT
## Content of this Repository
The code collected in this repository belongs to my Bachelors Thesis with the title 'Transformer Based Detection of 
Conspiracy Narratives in the Context of COVID-19 on German Social Media'. 

In the thesis I fine-tune BERT models to train a classifier to detect conspiracy in German Telegram data in the context 
of the COVID-19 pandemic.
It was written in the context of the project 'Digitaler Hass', a interdisciplinary project 'Digitaler Hass', which is 
a collaboration between Hochschule für Technik und Wirtschaft (HTW) Berlin and Alice Salomon University (ASH) Berlin.

The data used for this project was annotated in the context of the paper "Codes, Patterns and Shapes of Contemporary Online 
Antisemitism and Conspiracy Narratives an Annotation Guide and Labeled German-Language Dataset in the Context of COVID-19" 
(https://doi.org/10.48550/arXiv.2210.07934). Its corresponding Datasheet: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7093870.svg)](https://doi.org/10.5281/zenodo.7093870)


##Primary Purpose
The primary purpose of this repository is to demonstrate how results were performed. That's why for example no requirements.txt file is included.
To protect the privacy of the authors of the messages, both the raw data and models are omitted. Thus, the code would throw errors.  

The repo contains notebooks for:
1) Data Preparation
2) Model Training using the Transformers library (https://huggingface.co/docs/transformers/index) and PyTorch
3) Bayesian and Grid search hyperparameter tuning 
4) Domain Adaption of BERT model
5) Evaluation of Model Performance 
6) Some helpers

Furthermore it contains a configuration file which includes mostly hyperparameters. 

Please note: Not all code, and not all versions of the code have been uploaded. For example, the basic model training
notebook was adapted frequently to special needs (e.g. change loss function, (hyper)parameters).
For most parts, however it remained the same. Some code was also omitted as it wasn't considered very relevant.  