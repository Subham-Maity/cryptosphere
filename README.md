# Web3 Based Crypto Verse Application made By [Subham](https://subham-maity.github.io/subham/)

<hr>

### Frontend 
#### 1. Using RapidAPI ⭐
#### 2. ReactJS ⭐
#### 3. JS ⭐
#### 4. HTML ⭐
#### 5. CSS ⭐
### Smart contract for its functionality(backend) Using P2P network
#### 6. Solidity ⭐

<hr>

<h2 align=center>Contributors in This Project✨</h2>

Thanks to these **Wonderful People** 👨🏻‍💻 <br>
**Contributions** of any kind are welcome! 🚀

<table>
	<tr>
		 <td>
 <a href="https://github.com/Subham-Maity/cryptoapp/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Subham-Maity/cryptoapp" />
</a>
  </a>
		</td>
	</tr>
</table>

⭐ Star this repo on GitHub — it helps!
************
## Steps for making this project 

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

**11. Now again open terminal we can start by installing all the  necessary dependencies we can install  the dependencies by typing npm install  and now we can start listing all of the  dependencies  for styling we're going to use and  design so you can simply type antd  then we also need design so -design/ icons ... icons for the icons. We are also going to use redux, so you can  install react-redux @reduxjs/toolkit  then we're also going to use axios to  make api requests we're going to use  chart.js to create charts  we're going to use html react parser to  parse some html data we're also going to  use a hand a little package called millify that's going to transform  extremely large numbers into readable  strings  finally we're going to use moment to  parse times and dates, and we also need react-chartjs-2 to render those charts from  charges in our React application  there we go these are all the packages  that we need you can simply press enter ,and we're going to wait a few moments**

```txt
npm install antd @ant-design/icons react-redux @reduxjs/toolkit axios chart.js html-react-parser millify moment react-chartjs-2

```


**12. Now just type on the terminal after installation " npm start "**

```text
npm start 
```
- output will be react-scripts start

**13.** 
- Now open App.js and import this 
```text
import { Switch, Route, Link } from 'react-router-dom';
import { Layout, Typography, Space } from 'antd';
```
and delete the heading and create three div for navbar main and footer 

- Entire code like this 
```jsx
import React from 'react';
import { Switch, Route, Link } from 'react-router-dom';
import { Layout, Typography, Space } from 'antd';


const MyComponent = () => {
    return (
          <div className="app">
                <div className="navbar">
                </div>
                <div className="main">

                </div>
                <div className="footer">
                </div>
            </div>

    );
};

export default MyComponent;
```

**14. Create a folder in SRC folder name this folder as "components" and make a file Navbar.jsx inside components folder** 


**15. Type rfc for boilerplate in Navbar.jsx**

**16. For creating the navbar import some library** 
```text
import React, { useState, useEffect } from 'react';
import { Button, Menu, Typography, Avatar } from 'antd';
import { Link } from 'react-router-dom';
import { HomeOutlined, MoneyCollectOutlined, BulbOutlined, FundOutlined, MenuOutlined } from '@ant-design/icons';
```

