# Classifying sentences as suggestions or non-suggestions #

Suggestions were the project basis and extracting them from a piece of text was the challenge. Suggestions have the power to improve businesses and are pitched everywhere on the online web such as in review columns, Twitter and Reddit forums.

A competition was set by SemEval in 2019, which challenged everyone to produce a model that can classify a sentence as either a suggestion or non-suggestion.  Further details of this competition can ve found here: https://competitions.codalab.org/competitions/19955 
There are many challenges involved in extracting these sentences, such as suggestions being sparse in text and also being hard to identify as they come in many different forms. 

Through the use of research, critical analysis of methods and experiments, an ensemble model was created achieving an F1 score of 0.75. This ensemble model leveraged CNN and RNN models.
A plot of the confusion matrix is shown below: 

The following was used during this project:
* python 
* TensorFlow 
* BERT 
* numpy
* pandas 
* Google's cloud GPU 
* Colab notebook 
