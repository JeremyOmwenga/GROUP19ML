# GROUP19ML
A personalized medical assistant utilizing NLP
This is a personalized medical chatbot assistant utilizing Natural Language Processing.

## Key components:

### Frontend (HTML and CSS):

The user interacts with the chatbot through a user-friendly web interface built using HTML and styled with CSS.
The frontend displays the chat window where users can input their medical questions or concerns.

### Backend (Flask - Python):

The Flask framework handles the backend logic, routing, and communication between the frontend and the machine learning model.
Flask allows seamless integration of the chatbot with the web interface.

### Machine Learning Model (Keras):

The heart of the chatbot is a machine learning model trained using Keras.
The model is based on natural language processing (NLP) techniques and deep learning.
It learns from a dataset containing different medical intents (e.g., symptoms).
The model predicts the most relevant intent based on user input.

### Dataset (JSON file with intents):

The dataset consists of predefined intents, each associated with a set of example user queries.
For instance, an intent might be “symptoms,” and the associated queries could include “I have a headache” or “My throat hurts.”
The JSON file organizes these intents and their corresponding patterns.

### Chatbot Workflow:

When a user enters a query, the chatbot:
Preprocesses the input (tokenization, lemmatization, etc.).
Feeds it to the trained model.
Determines the intent (e.g., “symptoms,”).
Generates an appropriate response based on the intent.

