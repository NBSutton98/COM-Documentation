# Connecting to Github and Installing Nodemon

The following steps will explain how to connect our newly created file to your github, as well as install nodemon.
Nodemon will allow us to view our file and have it auto update, which will aleviate unecessary repitition.

## Github

1 Intiliaze github in VSCode<br>
2 Check our file by typing the following in the terminal: _node .\filename_<br>

```
node .\filename
```

3 Add the names of the files we created in the previous step to **.gitignore (node_module/\*)**<br>
![gitIgnore](<./Task2/gitIgnore(7).png>)

## Installing Nodemon

4 nagivate to the terminal as we did in our last step **(VIEW --> TERMINAL)**<br>

- Type the following: _npm install -g nodemon_

```
npm install -g nodemon
```

![Nodemon](./Task2/Nodemon.png)

5 We will start Nodemon by typing the following in the terminal: _nodemon .\filename.js_<br>

```
nodemon .\filename.js
```

![NodemonServer](./Task2/NodemonServer.png)

## Testing our file with Nodemon

6 Open up a browser and type the following: _localhost:3000/_<br>

```
localhost:3000/
```

![TestingServer](./Task2/serverTest.png)
7 Return back to the file and modify hello world response<br>
8 Change the port number from **3000** to another number from **1-64536**<br>
![TestingServer](./task3/listenBoilerPlate.png)
