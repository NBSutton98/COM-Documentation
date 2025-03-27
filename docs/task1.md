
# Getting Started with Express JS

In this section, we will go over the steps to installing and creating our first file.

## Creating our file
- Select new file that you will be creating
![NewFile](/Task1/NewFile(1).png)
- Name our file to whatever name of your choice, make sure to include **.js** at the end
![NewFile](/Task1/NameFile(2).png)

## Getting Started with Express JS
- Navigate to the terminal window by going to **VIEW --> TERMINAL**
  - This can also be done with the shortcut: *(CTRL + SHIFT + `)*
- Once the terminal has opened, click into it
- Type the following: *npm init*
![Init](/Task1/npmINIT(4).png)

## Copy over the boilerplate code
- We will next copy over the boilerplate code provided to us by Express
![BoilerPlate](/Task1/BoilerPlate(6).png)
- navigate to the [Express JS Setting Started](https://expressjs.com/en/starter/installing.html) website

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
- Add req Object to test functionality (what does this do)



## Installing express
- After we have typed **npm init**, we will be asked to enter details about our file
```
npm init
```
- Continuously press *ENTER* until all done
- Navigate to the newly created **package.json** that npm has created for us
- Verify the names inside **package.json** match what we have installed
![package](/Task1/verifyResults(7).png)
- Type the following: *npm install express*
```
npm install express
```
![Express](/Task1/intialization(3).png)
- To verify we did the last steps correctly, type the following into the terminal: *node .\filename*


