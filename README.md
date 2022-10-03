# Healthcare-chatbot Using machine learning and natural language prcessing

Healthcare is very important to lead a good life. However, it is very difficult to obtain a consultation with a doctor for every health problem. The idea is to create a medical chatbot using Artificial Intelligence that can diagnose the disease and provide basic details about the disease before consulting a doctor. This will help to reduce healthcare costs and improve accessibility to medical knowledge through medical chatbots

Run Locally

Clone the project

  git clone https://github.com/robinsingh051/Healthcare-chatbot

Go to the project directory

  cd Healthcare-chatbot

Install dependencies

  pip install rasa
  pip install flask
  pip install requests

Go to rasabot directory

  cd rasabot

open terminal in this directory and run the following command to start rasa server

  rasa run -m models --endpoints endpoints.yml --port 5002 --credentials credentials.yml

Go to web_app directory

  cd web_app

open terminal in this directory and run the following command to start flask server

    flask run
