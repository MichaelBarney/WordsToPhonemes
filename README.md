
# WordsToPhonemes
A Machine Learning model that is able to translate written english words to their corresponding Phonemes.

This project is a Keras implementation of the Model presented as part of my certification in Microsfoft's Natural Language Processing (NLP) course, being heavily inspired by its presented content

This Machine Learning algorithm has the objective of creating a Sequence-To-Sequence NLP model that is capable of translating a word input to its corresponding phonemes in the  **_arpabet_**  format.

For example, it is able to receive the word "**car**" and return the phonemes "**K AA R**".



It uses the Keras library to create an LSTM Recurrent Neural Network to be trained with thousands of english words gathered from the [CMUDict](http://www.speech.cs.cmu.edu/cgi-bin/cmudict).

The created Jupyter Notebook is greatly documented, and can be found [here](https://github.com/MichaelBarney/WordsToPhonemes/blob/master/Word2Phonemes.ipynb).

If you wish to use the model I trained when creating this project, it is found directly in the file [s2s.h5](https://github.com/MichaelBarney/WordsToPhonemes/blob/master/Word2Phonemes.ipynb)
