Overview:
This project features an intelligent chatbot that uses Natural Language Processing (NLP) to understand user inputs and respond meaningfully. Designed with a simple and clean Streamlit interface, the chatbot delivers an engaging and interactive experience. It is highly customizable and ideal for applications like FAQs, customer support, and educational tools.

Features:
Intent Recognition: Identifies the user’s intent using Logistic Regression trained on labeled patterns.
Web-Based Interface: User-friendly chatbot interface built with Streamlit.
Conversation Logs: Automatically saves all conversations, including timestamps, for tracking or analysis.
Predefined Responses: Responds based on a structured intents.json file for accuracy and clarity.
Easy Expansion: New intents and responses can be added effortlessly to enhance functionality.

Technologies Used:

NLP Tools:
nltk for tokenization and preprocessing user inputs.
TF-IDF Vectorizer for transforming text into numerical features.
Machine Learning:
Logistic Regression for intent classification.
Frontend:
Streamlit for creating a seamless and interactive web application.
Data Format:
JSON file for defining intents and response patterns.
