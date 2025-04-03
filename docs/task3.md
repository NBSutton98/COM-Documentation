# Using Get\Send\Listen

In the next steps, we will go over how to start using get, send and listen in Express JS.

## Use the Get Request Boilerplate

<br>**1** We will paste this new boilerplate code into our VSCode, replacing the preivous code<br>

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

    The boilerplate code can also be found at this [website](https://expressjs.com/en/starter/hello-world.html)

## Getting started with res.send

<br>**2** Type the following in the terminal: **node .\server.js**, and refresh the page to verify that the server is running<br>

```
node .\server.js
```

!!! info "Info"

    In the same terminal, the program can be stopped by typing the following: **CTRL + UPPERCASE C_**

!!! warning "Warning"

    If the program is stopped using **CTRL + UPPERCASE C** is used, nodemon must be restarted again before continuing again using the following code:
    ```
    nodemon .\filename.js
    ```

<br>**3** We are then changing our **app.get** to the following, replace the previous **app.get** with this code<br>

```
app.get("/", (req, res) => {
    res.send("<h1> Welcome to my first site!</h1>")
})
```

## Testing our app.listen

We will now test our **app.listen** message to view what we just created with **res.send**

<br>**4** Open up a browser of your choice and type: _localhost:3000_<br>

```
localhost:3000
```

<br>**5** We will now check our generic message in the browser<br>
!!! success "Success"

    Your page should look like this: <br>
    ![message](./task3/listenTest.png)

## Using res.send for a new page

<br>**6** We will now go back to vsCode to send a message to a new page. Copy the following code to replace our old **app.get**:<br>

```
app.get("/page1", (req, res) => {
    res.send("<h1> Welcome to page1!</h1>")
})
```

<br>**7** Let's test this page by the /page route and check our result <br>
!!! success "Success"

    Your page should look like this: <br>
    ![pageTest](./task3/chnagePageTest.png)
