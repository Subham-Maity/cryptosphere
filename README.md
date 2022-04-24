# Create Crypto App

**1. First create a folder without space** 

**2. Open this folder through vs code/WebStorm(My Recommendation)** 

**3. open terminal and type** 
```text
npx create-react-app ./
```
**and wait for 1-2 minutes** 

**4. Delete the source folder which already made and create a source folder by yourself**

**5.Create index.js inside the SRC folder and Import this** 
```jsx
import React from 'react';
import ReactDOM from 'react-dom';
import App from './App';
ReactDOM.render(<App/>, document.getElementById ('root'));
```
ReactDOM.render then inside here we need to pass this app as a component as a first parameter and then finally say
document.getElementById then '**root**' to hook our app onto our root div


**6. behind the scenes this means that we have a public with one index.html file now this html file looks a bit weird at the start but Remove some space and commends and make it as a simple html file** 

like this 
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <link rel="icon" href="%PUBLIC_URL%/favicon.ico" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="theme-color" content="#000000" />
    <meta name="description" content="Web site created using create-react-app"/>
    <link rel="apple-touch-icon" href="%PUBLIC_URL%/logo192.png" />
    <link rel="manifest" href="%PUBLIC_URL%/manifest.json" />
    <title>React App</title>
  </head>
  <body>
  <div id="root"></div>
  </body>
</html>

```
- You can copy this and paste on your index file 

7. 



