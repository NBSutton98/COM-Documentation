# Connecting a website using Express

In these steps, we will finally connect our web page using express.

## Creating a template HTML page

1 Create a new html file<br>

- Name the file: _home.html_

![renameHTML](./Task4/renameHTML.png)

2 Once the file is created, click into it<br>
   At the top of the page, we will be utilizing a shortcut to make a boilerplate html page
3 Copy the following text and paste it into your new file<br>

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

4 Add a message inside the<br>
   ![HTML](./Task4/intializeHTML.png)

5 Lets verify that our html page is working by checking our localhost:3000!<br>
   ![HTML](./Task4/htmlMsgCheck.png)

## Connecting our website through express

6 Go back to our other file where the .send is<br>

- copy the destination path to the html page we just created
- Update our app.get

  ![reinitGet](./Task4/reintializeGet.png)

## Testing our new website with app.get

with our new get request, we can now test our new website!

7 lets add a messgae to our json object<br>
![get](./Task4/appGetMessage.png)

8 navigate to localhost:3000 and you should see the new addition<br>
![jsonViewer](./Task4/jsonViewerTest.png)

## Installing json viewer and testing our new website

9 go to extensions page <br>

- search for json viewer
- download extension
- use extension to test our website
  ![jsonViewer](./Task4/jsonViewer.png)
  10 once extension is downloaded you visit your localhost:3000 and you should see the new addition<br>
  ![jsonViewerTest](./Task4/jsonViewerTest.png)
  11 selecting the parse option will allow us to see our json object in a user friendly way<br>
  ![jsonViewerParse](./Task4/jsonViewerParse.png)
