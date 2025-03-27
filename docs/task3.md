# Using Get\Send\Listen

In the next steps, we will go over how to start using get, send and listen in Express JS.

## Use the Get Request Boilerplate 
- Copy the Get request from the website and paste it into your file
```
const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Hello World!')
})

app.listen(port, () => {
  console.log(`Example app listening on port ${port}`)
})
```
- This boilerplate can also be found [here](https://expressjs.com/en/starter/hello-world.html)

## Getting started with res.send
- Explain how res.send will send a message

- Type the following in the terminal: **node .\filename**
```
node .\filename
```
- server update (kill and restart)
- In the same terminal, the program can be stopped by typing the following: *CTRL + UPPERCASE C*


## working withapp.listen
- Change our **app.listen message to custom message
- open up a browser of your choice and type: *localhost:3000\*
```
*localhost:3000\*
```
- see our custom message
