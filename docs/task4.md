# Connecting a website using Express

In these steps, we will finally connect our web page using express.

## Creating a template HTML page

- Create a new html file
- Name the file: _home.html_

![renameHTML](./Task4/renameHTML.png)

- Once the file is created, click into it
- At the top of the page, we will be utilizing a shortcut to make a boilerplate html page
- Copy the following text and paste it into your new file

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

</body>
</html>
```

- Add a message inside the <body>

## Connecting our website through express

- Go back to our other file where the .send is
- copy the destination path to the html page we just created
- Update our app.get

  ![reinitGet](./Task4/reintializeGet.png)
  
- res.json boiler w/ message

## Testing our new website with app.get

- with our new get request, we can now test our new website!

- lets add a messgae to our json object

  ![get](./Task4/appGetMessage.png)

- navigate to localhost:3000 and you should see the new addition

  ![jsonViewer](./Task4/jsonViewerTest.png)



## Installing json viewer and testing our new website

- go to extensions page
- search for json viewer
- download extension
- use extension to test our website
  ![jsonViewer](./Task4/jsonViewer.png)

- once extension is downloaded you visit your localhost:3000 and you should see the new addition
  ![jsonViewerTest](./Task4/jsonViewerTest.png)

- selecting the parse option will allow us to see our json object in a user friendly way
  ![jsonViewerParse](./Task4/jsonViewerParse.png)
