# Chatbot
A smart conversational AI chatbot built with Python and Natural Language Processing (NLP) to understand and respond to user queries naturally. This project demonstrates core NLP techniques such as tokenization, lemmatization, and contextual response generation.

# Chatbot using Python and NLP

This project is a simple conversational chatbot implemented in Python that uses Natural Language Processing (NLP) techniques to understand and respond to user queries. The chatbot leverages sentence tokenization, TF-IDF vectorization, cosine similarity, and basic keyword matching to generate appropriate responses.

## Features
- Greeting recognition and response
- Responses based on keyword matching with TF-IDF and cosine similarity
- Handles small talk and general queries about chatbots
- Continues conversation until user decides to exit

## How it works
- Reads a corpus file named `chatbot.txt` which contains the data used to generate responses.
- Preprocesses input and corpus with tokenization, lemmatization, and removal of punctuation.
- Checks for greetings and responds accordingly.
- For other inputs, computes cosine similarity to find the most relevant sentence in the corpus and responds with it.
- If no relevant sentence is found, informs the user that it doesn't understand.

## Usage
- Ensure you have a text file named `chatbot.txt` in the same directory containing your corpus data.
- Run the Python script. The chatbot will start and interact with you in the console.
- Type your queries or greetings, and the chatbot will respond accordingly.
- Type `Bye` to exit the conversation.

