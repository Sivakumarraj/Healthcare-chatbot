# Healthcare-chatbot
How to create an Healthcare chatbot using rasa Software to increase the efficiency of time,and increase the accuracy of treatment
  pip install rasa
    pip install flask
      pip install requests
#Go to rasabot directory
  cd rasabot
#open terminal in this directory and run the following command to start rasa server
  rasa run -m models --endpoints endpoints.yml --port 5002 --credentials credentials.yml
#Go to web_app directory
  cd web_app
#open terminal in this directory and run the following command to start flask server
    flask run
