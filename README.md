# NLP_Humor_Prediction

## Natural Language Processing coursework for MSc AI at Imperial College London, academic year 2020-2021. The final code was submitted to Codalab's 2020 competition - taks 7: "Assessing the Funniness of Edited News Headlines"
 
News headlines were edited in two different ways, and the assigment's main task was to predict which of each pair of edits was funnier. A labelled dataset was provided by Codalab's competition organizers.

We implemented different approaches divided in two categories:

* With pre-trained embeddings - This section includes six different versions of the BERT model. The second model includes  hyperparameter search
* Without pre-trained embeddings
  * FFNN - To evaluate 'funniness' of individual words
  * CBOW - For headline classification based on the compatibility of the original headline and the edit word

The file can be run as is, with the first two code cells including the libraries that need to be installed
