# chatbot
Project Overview:
This project is a simple chatbot application built using Tkinter for the GUI and Natural Language Processing (NLP) techniques for text processing. The chatbot interacts with users via a graphical interface and provides responses based on the content of a Wikipedia article.

Key Features:
Web Scraping: The chatbot fetches data from a Wikipedia page using BeautifulSoup.
Tokenization: The text is tokenized into sentences and words using nltk.
Text Normalization: Lemmatization and stopword removal are applied for better text understanding.
TF-IDF Vectorization: The chatbot uses TF-IDF (Term Frequency-Inverse Document Frequency) to find similarity between user input and the text from the Wikipedia page.
Cosine Similarity: Responses are based on the similarity between the user input and sentences from the scraped text.
Greeting Responses: The chatbot can recognize common greetings and respond appropriately.
Graphical User Interface (GUI): The user interacts with the chatbot using a GUI built with Tkinter.
Technologies Used:
Python: The programming language used to build the application.
Tkinter: For creating the graphical user interface.
NLTK: For text processing, including tokenization, stopword removal, and lemmatization.
BeautifulSoup: For web scraping to extract data from the Wikipedia page.
Requests: For making HTTP requests to fetch webpage content.
Scikit-learn: To perform TF-IDF vectorization and calculate cosine similarity.
