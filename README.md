# Finetuned DialoGPT on Movie Dialogues
Team Member: Jieqian Liu(jl2750), Jieyi Sun(js4958), Zidong Xu(zx92), Minglei Cai(mc2582)

Report Website: https://kianakaslana648.github.io/nlp-final-project/#

## Project Goals
For our project, we place our interests and efforts on the open-domain chatbots. We expect to build an open-domain chatbot with dramatic responses, which has the ability of 'chatting' with the user in an interesting and interactive way. Our business goal is to give the user a surprise, a sense of happiness, and a relief temporarily from the heavy everyday work and studies. Our basic idea is finetune the pre-trained **microsoft dialoGPT** dialogue systems on the movie dialogue corpus and deploy the chatbots using the API provided by **google voice**.

## Datasets
### Movie Dialogue Corpus:
https://www.kaggle.com/datasets/Cornell-University/movie-dialog-corpus

The corpus contains a metadata-rich collection of fictional conversations extracted from raw movie scripts:

* 220,579 conversational exchanges between 10,292 pairs of movie characters
* involves 9,035 characters from 617 movies
* in total 304,713 utterances

## Pre-trained Models
Seq2seq transformers from huggingface community:  
* DialoGPT-small; DialoGPT-medium; DialoGPT-large.

## Tutorial

### Data Cleaning
* You can follow the tutorial notebook **Movie_DialoGPT_train.ipynb** for the data-cleaning process. Currently we only make use of the subset dialogues of movies tagged with 'comedy'.

### Finetuning Process
* You can follow the tutorial notebook **Movie_DialoGPT_train.ipynb** for the fine-tuning process.

### Deploy using Google Voice
* You need to first configure **client_secret.json** and **gmail_token.json** and add them to your work directory. Please refer to google voice documentation for details.
* Then you can run the **googlevoice.ipynb** and send message to your google voice number for interaction.

## Demos
See screen recordings in the 'demos' folder.

## External Links:
* Huggingface: https://huggingface.co/Kiana648/movie_dialogue_gpt2
