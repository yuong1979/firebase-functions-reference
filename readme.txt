##After cloning

#install firebase tools
npm install -g firebase-tools

#check if the firebase tools has been installed
firebase --version

#authenticate through login
firebase login

#Change directory into the function folder first
#Install axios
npm install axios

#change directory into the main folder before running the emulator
firebase emulators:start

#open a window with url http://localhost:4000/ or check the port you were assigned with during the init

#Deployment (add only functions if you want to deploy only functions)
firebase deploy --only functions








##Start from scratch 

#install firebase tools
npm install -g firebase-tools

#check if the firebase tools has been installed
firebase --version

#authenticate through login
firebase login

#Set up a new project on firebase console - https://console.firebase.google.com/ and create a new project and database inside the project
#create the folder that you want to create the application in and
#Change the directory into the folder and initialize firebase
firebase init -  Go through the steps in setting up firebase on cli
#install firestore, functions, emulators - select default choices, for emulators select pubsub, authentication, functions, firestore

#Initialize the emulators to simplify testing if this step hasnt been done
firebase init emulators

#install axios
#change directory into the functions folder
npm install axios

#insert code into index.js in the functions folder

#run the emulator
firebase emulator:start

#Deployment (add only functions if you want to deploy only functions)
firebase deploy --only functions

#refer to https://youtu.be/gA6WGYQWrKc for full tutorial

