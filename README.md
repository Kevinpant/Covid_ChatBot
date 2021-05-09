
# Hospital Beds Availability ChatBot

In this project I create a ChatBot which automatically fetches details of Hospitals with Vacant ICU beds and Non ICU beds, using webscrapping.
The chatbot spits out vrious important details such as contact number, Hospital name, location, vacant beds with and without ICU beds, etc.


***Project Setup:***

First, pull the git repository on your system with the given command:
git clone https://github.com/Kevinpant/Covid_ChatBot.git

Sep 1:  pip install -r requirements.txt
This will install all the dependencies for your project so that you can get started with the project and test it's functionality. It will take some time to setup and install all the packages on your system.

Now when you have all the dependencies installed, run the given commands parallelly on two terminals to start the action server and the rasa server.

rasa run --model models --enable-api --cors "*" --debug

and in Second Terminal run the following command:
rasa run actions

With these commands the rasa chatbot gets activated and we are now ready to interact with out smartbot.
Final step is to open index.html file on the browser and enjoy playing around with our chatbot.

