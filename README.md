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
    <title>CryptoApp</title>
  </head>
  <body>
  <div id="root"></div>
  </body>
</html>

```
- You can copy this and paste on your index file 

**7. Make an app.js inside the SRC file** 

**8. Simple type rsc in WebStorm / type rafce in Vscode(install this app plugins ES7 React/Redux/GraphQL/React-Native snippets)** 

for this boilerplate 

```jsx
import React from 'react';

const MyComponent = () => {
    return (
        <div>

        </div>
    );
};

export default MyComponent;

```

**9. Now add heading 'Cryptoverse' like this**

```jsx
import React from 'react';

const MyComponent = () => {
    return (
        <div>

            <h1>Cryptoverse</h1>

        </div>
    );
};

export default MyComponent;
```

**10. Open your terminal and type 'npm start'(allow network) and look at your browser** 
```text
npm start
```
 
- For terminate the app just type on your terminal "Ctrl" + "C" and press Y
- then type clear for clear the terminal 
```text
clear
```

**11. we can start by installing all the  necessary dependencies we can install  the dependencies by typing npm install  and now we can start listing all of the  dependencies  for styling we're going to use and  design so you can simply type and d  then we also need and dash design  forward slash icons for the icons we are  also going to use redux so you can  install react dash redux and add redux  js forward slash toolkit  then we're also going to use axios to  make api requests we're going to use  chart.js to create charts  we're going to use html react parser to  parse some html data we're also going to  use a hand a little package called  milify that's going to transform  extremely large numbers into readable  strings  finally we're going to use moment to  parse times and dates  and we also need react dash chart js  dash 2 to render those charts from  charges in our react application  there we go these are all the packages  that we need you can simply press enter  and we're going to wait a few moments**

```txt
npm install antd @ant-design/icons react-redux @reduxjs/toolkit axios chart.js html-react-parser millify moment react-chartjs-2

```



