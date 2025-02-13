High level description

Primitive RAG system without usind dabases to store embeddings

-----------------------------

Introduction

The goal of this project is to enhance a GPT model's ability to provide accurate and updated answers about news events from 2022. 
By embedding Wikipedia news articles and implementing a similarity retrieval mechanism, the model can deliver contextually relevant responses based on recent information.

-----------------------------

Features

Wikipedia API Integration: Automatically retrieves significant news events from Wikipedia for the year 2022.
GPT Model Querying: Compares the responses of the non-optimized and optimized GPT models.
Embedding and Similarity Retrieval: Uses embeddings to enhance the model's understanding and retrieval of relevant information.
Contextual Answers: Optimized model provides updated and contextually accurate responses to news-related queries.

-----------------------------

Prerequisites

Python 3.8 or higher
Jupyter Notebook
Required Python libraries: openai, requests, dateutil.parser, tiktoken, pandas
