# Getting Started with Express JS

In this section, we will go over the steps to installing and creating our first file.

## Creating our file

<br>**1** Select new file that you will be creating<br>

![NewFile](<./Task1/NewFile(1).png>)

<br>**2** Name our file to whatever name of your choice, make sure to include **.js** at the end
![NewFile](<./Task1/NameFile(2).png>)

## Getting Started with Express JS

Next we will install Express from the terminal

<br>**3** Navigate to the terminal window by going to **VIEW --> TERMINAL**

!!! info "Info"

    This can also be done with the shortcut: \_(CTRL + SHIFT + `)

<br>**4** Once the terminal has opened, click into it and typee the following into the terminal: _npm install express_

```
npm install express
```

## Copy over the boilerplate code

<br>**5** We will next copy over the boilerplate code provided to us by Express

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

!!! info "Info"

    This code can also be found on the [Express JS Setting Started](https://expressjs.com/en/starter/installing.html) website

## Getting started with npm

<br>**6** Navigate to the terminal window by going to **VIEW --> TERMINAL**<br>

!!! info "Info"

    This can also be done with the shortcut: _(CTRL + SHIFT + `)_

<br>**7** Once the terminal has opened, click into it and type the following: _npm init_<br>
![Init](<./Task1/npmINIT(4).png>)

```
npm init
```

!!! info "Info"

    After we have typed **npm init**, we will be asked to enter details about our file

<br>**8** Continuously press _ENTER_ until all done

## Checking our steps

<br>**9** Navigate to the newly created **package.json** that npm has created for us<br>
![package](<./Task1/verifyResults(7).png>)

<br>**10** Verify the names inside **package.json** match what we have installed<br>
![Express](<./Task1/intialization(3).png>)

<br>**11** To verify we did the last steps correctly, type the following into the terminal: _node .\filename_

```
node .\filename
```

<br>**12** Finally add a .gitignore file to our project, this will allow us to upload our file to github<br>
!!! success "Success"

    Your page should look like this: <br>
    ![gitIgnore](./Task1/gitIgnore.png)
