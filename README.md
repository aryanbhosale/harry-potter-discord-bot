# Harry Potter Discord AI ChatBot

This is a Discord AI Chatbot that uses the [Microsoft DialoGPT conversational model](https://huggingface.co/microsoft/DialoGPT-medium) fine-tuned on the book transcript of [Harry Potter](https://en.wikipedia.org/wiki/Harry_Potter) (HP). 

I trained the model using the lines of my favorite quirky character, Harry Potter. He has about 155 lines in total in the transcript I used.

You can directly chat with the model hosted on [Hugging Face's Model Hub](https://huggingface.co/aryanbhosale/DialoGPT-medium-harrypotter).

## Structure of this Project

- `model_train_upload_workflow.ipyb`: Notebook to be run in Google Colab to train and upload the model to Hugging Face's Model Hub
- `discord_bot.py`: Script to be imported into a replit.com Python Discord.py project

## Resource Links

- [My Harry Potter dataset on Kaggle](https://www.kaggle.com/gulsahdemiryurek/harry-potter-dataset?select=Harry+Potter+1.csv)
- [My Hugging Face Model](https://huggingface.co/aryanbhosale/DialoGPT-medium-harrypotter)
