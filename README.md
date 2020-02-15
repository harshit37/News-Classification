# News-Classification
Program to classify news based on headlines and short description , there were 37 categories such as environment,sports,politics,parenting etc
# Language Model
Fine tuning the LANGUAGE model for our dataset , this model was pretrained on WIKITEXT-103 
# Classifier
Classifier created a new data object(data_class) that only grabs the labelled data and keeps those labels(as per folder name ) 
data_clas.show_batch()-- helped to see a batch in which ​tokenized and numericalized news was labelled.
​Downloaded the classifier model as well as loaded the previous encoder(lang model), after which model was trained on optimal learning rates .
Model was saved at various places as a checkpoint to get back the previous model in case of overfitting. 
