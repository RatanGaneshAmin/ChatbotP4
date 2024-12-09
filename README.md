
# Chatbot with Natural Language Processing (NLP)
## Introduction
This project implements a chatbot using Natural Language Processing (NLP) techniques. The chatbot is designed to recognize user intents and generate suitable responses based on predefined patterns and responses. It utilizes the NLTK library for NLP tasks, Scikit-learn for machine learning, and Streamlit to create an interactive web-based interface.

## Key Features
Understands various user intents such as greetings, farewells, and expressions of gratitude.
Provides accurate and relevant responses tailored to user inputs.
Maintains a log of conversation history that users can access.
Built with Python and integrates several popular NLP and machine learning libraries.

## Technology Stack
Python
NLTK
Scikit-learn
Streamlit
JSON for managing chatbot intents data

## Setup Instructions

## Clone the Repository:
Download the repository to your local machine.

## Set Up a Virtual Environment (Optional):
Create and activate a virtual environment to isolate project dependencies.

## Install Dependencies:
Install the required libraries listed in the requirements.txt file.

## Download NLTK Data Files:
Use the NLTK library to download necessary data files, such as tokenizers.

## Running the Application
To run the chatbot, start the Streamlit application. Once the application is running, interact with the chatbot through the web interface by typing messages in the input field. The chatbot will provide appropriate responses based on your queries.

## Customizing Intents
The chatbot’s behavior is defined by an intents.json file, which includes tags, patterns, and their corresponding responses. You can modify this file to add new intents or update existing ones to suit your requirements.

## Conversation History
The chatbot saves all interactions in a CSV file named chat_log.csv. This allows users to view and analyze previous conversations. The conversation history can also be accessed from the "Conversation History" option in the sidebar of the chatbot's interface.

## Contributing
Contributions to this project are welcome. If you have ideas for improvements or want to add new features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. Refer to the LICENSE file for further details.

## Acknowledgments
NLTK for enabling natural language processing functionalities.
Scikit-learn for its robust machine learning algorithms.
Streamlit for creating an interactive and user-friendly web application interface.

