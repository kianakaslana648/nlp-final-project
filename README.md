# Chatbot for Movie Script

## Basic Introduction
* A chatbot you can chat with by sending messages whenever you want.  

We finetune the pre-trained **microsoft dialoGPT** dialogue systems on the movie dialogue corpus. And finally deploy the chatbots using the API provided by **google voice**.


## Datasets
### Movie dialogue corpus:
https://www.kaggle.com/datasets/Cornell-University/movie-dialog-corpus

The corpus contains a metadata-rich collection of fictional conversations extracted from raw movie scripts:

* 220,579 conversational exchanges between 10,292 pairs of movie characters
* involves 9,035 characters from 617 movies
* in total 304,713 utterances

## Pre-trained Models
Seq2seq transformers from huggingface community:  
$\qquad$ DialoGPT-small; DialoGPT-medium; DialoGPT-large.



## Tutorial
You can follow the tutorial ipynb for the fine-tuning process.
