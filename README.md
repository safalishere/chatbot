# Chatbot
Building a Simple Chatbot from Scratch in Python (using NLTK)
Alt text

History of chatbots dates back to 1966 when a computer program called ELIZA was invented by Weizenbaum. It imitated the language of a psychotherapist from only 200 lines of code. You can still converse with it here: Eliza.

On similar lines let's create a very basic chatbot utlising the Python's NLTK library.It's a very simple bot with hardly any cognitive skills,but still a good way to get into NLP and get to know about chatbots.

Outline
Motivation
Blogpost
Pre-requisites
How to run
Motivation
The idea of this project was not to create some SOTA chatbot with exceptional cognitive skills but just to utilise and test my Python skills.This was one of my very first projects, created when I just stepped into the world of NLP and I thought of creating a simple chatbot just to make use of my newly acquired knowledge.

BlogPost
For detailed overview, here is the accompanying blog titled:Building a Simple Chatbot in Python (using NLTK)

Pre-requisites
NLTK(Natural Language Toolkit)

Natural Language Processing with Python provides a practical introduction to programming for language processing.

For platform-specific instructions, read here

Installation of NLTK
pip install nltk
Installing required packages
After NLTK has been downloaded, install required packages

import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
How to run
Jupyter Notebook Binder
You can run the chatbot.ipynb which also includes step by step instructions.

Through Terminal
python chatbot.py
