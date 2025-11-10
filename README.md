Boolean Retrieval System
This repository contains a simple implementation of a boolean retrieval system. It indexes a collection of text documents and allows users to perform boolean queries (AND, OR, NOT) to retrieve relevant documents.

Project Structure
The project consists of a Python notebook with the following main components:

Document Loading: Reads text documents from specified files into a dictionary.
Preprocessing: Cleans the text by converting to lowercase, removing punctuation, and removing stopwords.
Inverted Index Construction: Builds an inverted index that maps each unique word to the documents it appears in.
Boolean Retrieval: Implements boolean search logic (AND, OR, NOT) using the inverted index.
Setup

