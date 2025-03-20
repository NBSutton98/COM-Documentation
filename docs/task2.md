# Connecting to Github and Installing Nodemon

The following steps will explain how to connect our newly created file to your github, as well as install nodemon.
Nodemon will allow us to view our file and have it auto update, which will aleviate unecessary repitition.

## Github
- intiliaze github in vs code
- check our file using *node .\filename*
- add the names of the files we created in the previous step to **.gitignore (node_module/*)**
  
## Installing Nodemon
- nagivate to the terminal as we did in our last step (VIEW --> TERMINAL)
- Type the following: *npm install -g nodemon*
- We will start nodemon by typing the following: *nodemon .\filename.js*

## Testing our file with Nodemon
- open up a browser and type the following: *localhost3000/*
- Return back to the file and modify hello world response 
- Change the port number from 3000 to another number from **1-64536**
