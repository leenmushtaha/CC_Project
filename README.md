# CC_Project

##Project Description
This project focuses on building an initial system to analyze user chat messages through two main stages. In the first stage, PySpark was used to load and preprocess synthetic chat data in JSON format—extracting the key fields: text, intent, and sentiment—and the data was cleaned and analyzed for frequent intent and sentiment patterns. In the second stage, a deep learning model using TensorFlow and LSTM was built and trained to classify each message into intent and sentiment categories: the data was tokenized, encoded, and split into training and testing sets, and results show the model can reasonably predict both intent and sentiment. Additionally, Firebase was used to store real-time chats between the user and the bot, laying the groundwork for future extensions such as response generation and deeper cloud integration.

##Instructions
Download the dataset in the repository to be able to run the src code. 
!!Warning, the firestore section for saving entries won't work as the service code JSON key file won't be given. However, you may switch our link with yours.
