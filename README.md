# Finetuned DialoGPT on Movie Dialogues
## Basic Introduction
* A chatbot you can chat with by sending messages whenever you want.  

We finetune the pre-trained **microsoft dialoGPT** dialogue systems on the movie dialogue corpus. And finally deploy the chatbots using the API provided by **google voice**.


## Datasets
### Movie Dialogue Corpus:
https://www.kaggle.com/datasets/Cornell-University/movie-dialog-corpus

The corpus contains a metadata-rich collection of fictional conversations extracted from raw movie scripts:

* 220,579 conversational exchanges between 10,292 pairs of movie characters
* involves 9,035 characters from 617 movies
* in total 304,713 utterances

## Pre-trained Models
Seq2seq transformers from huggingface community:  
$\qquad$ DialoGPT-small; DialoGPT-medium; DialoGPT-large.



## Tutorial

### Finetuning Process
* You can follow the tutorial notebook **Movie_DialoGPT_train.ipynb** for the fine-tuning process.

### Deploy on Google Voice
* You need to first configure **client_secret.json** and **gmail_token.json** and add them to your work directory. Please refer to google voice documentation for details.
* Then you can run the **googlevoice.ipynb** and send message to your google voice number for interaction.
