
# Getting Started with Express JS

In this section, we will go over the steps to installing and creating our first file.

## Creating our file
- Select new file that you will be creating
  
![NewFile](./Task1/NewFile(1).png)

- Name our file to whatever name of your choice, make sure to include **.js** at the end

![NewFile](./Task1/NameFile(2).png)

## Getting Started with Express JS
- Next we will install Express from the terminal
- Navigate to the terminal window by going to **VIEW --> TERMINAL**
- This can also be done with the shortcut: *(CTRL + SHIFT + `)*
- Once the terminal has opened, click into it
- Type the following into the terminal: *npm install express*
```
npm install express
```

## Copy over the boilerplate code
- We will next copy over the boilerplate code provided to us by Express
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
- this code can also be found on the [Express JS Setting Started](https://expressjs.com/en/starter/installing.html) website


## Getting started with npm
- Navigate to the terminal window by going to **VIEW --> TERMINAL**
- This can also be done with the shortcut: *(CTRL + SHIFT + `)*
- Once the terminal has opened, click into it

  ![Init](./Task1/npmINIT(4).png)
- Type the following: *npm init*
```
npm init
```

- After we have typed **npm init**, we will be asked to enter details about our file
- Continuously press *ENTER* until all done

## Checking our steps
- Navigate to the newly created **package.json** that npm has created for us
  
![package](./Task1/verifyResults(7).png)

- Verify the names inside **package.json** match what we have installed

![Express](./Task1/intialization(3).png)

- To verify we did the last steps correctly, type the following into the terminal: *node .\filename*
```
node .\filename
```

- Finally add a .gitignore file to our project, this will allow us to upload our file to github.
![gitIgnore](./Task1/gitIgnore.png)


