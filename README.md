# Web3 Based Crypto Verse Application made By [Subham](https://subham-maity.github.io/subham/)

<hr>

## Working Frameworks

### 1. Frontend 
⭐ **Using RapidAPI** 
⭐ **ReactJS** 
⭐ **JS** [learn javascript from my js bootcamp [here](https://github.com/Subham-Maity/js-bootcamp)]
⭐ **HTML**[learn HTML from my HTML bootcamp [here](https://github.com/Subham-Maity/html-tutorial-for-beginners)]
⭐ **CSS**  /Tailwind

### 2. Smart contract for its functionality(backend) Using P2P network

⭐ **Solidity** 
- learn solidity from my Solidity bootcamp [here](https://github.com/Subham-Maity/solidity-tutorial)

(Solidity is an object-oriented, high-level language for implementing smart contracts on various blockchain platforms, most notably, Ethereum)

### 3. Api 
⭐ [**Coin Ranking Api**](https://rapidapi.com/Coinranking/api/coinranking1/)
⭐ [**Paw**](https://paw.app/)

### 4.Blockchain
⭐ **Ethereum Blockchain**

- learn blockchain from my documentation from [here](https://github.com/Subham-Maity/blockchain-basic)
- learn Ethereum from my documentation from [here](https://github.com/Subham-Maity/ethereum-tutorial)
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
```js
//index.js
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
<!--index.html-->
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
//App.js
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
//App.js
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
```js
//App.js
import { Switch, Route, Link } from 'react-router-dom';
import { Layout, Typography, Space } from 'antd';
```
and delete the heading and create three div for navbar main and footer 

- Entire code like this 
```jsx
//App.js
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
```jsx
//navbar.js
import React, { useState, useEffect } from 'react';
import { Button, Menu, Typography, Avatar } from 'antd';
import { Link } from 'react-router-dom';
import { HomeOutlined, MoneyCollectOutlined, BulbOutlined, FundOutlined, MenuOutlined } from '@ant-design/icons';
```
**17. We are gonna use some components(avatar,typography from antd) for this project and for now don't use button we are using it for phone later** 

- [ For more design you can find all the design from [**here**](https://ant.design/) ]

let's do this in your navbar.jsx for adding avatar typography and so on 

```jsx
<!--Navbar.js-->
<div className="nav-container">
      <div className="logo-container">
        <Avatar/>
        <Typography.Title level={2} className="logo">
            <Link to="/">Cryptoverse</Link></Typography.Title>
        {/*<Button className="menu-control-container" onClick={() => setActiveMenu(!activeMenu)}><MenuOutlined /></Button>*/}
      </div>
    </div>
```


**18. Now we are gonna add icon for our avatar you can download it from** [**here**](https://i.ibb.co/Z11pcGG/cryptocurrency.png)
- make a folder "images" in src folder 
- download the [image](https://i.ibb.co/Z11pcGG/cryptocurrency.png) and paste it on the images folder
- and drag it on to our image folder 
- edit the html avatar tag like this
```html
<!--Navbar.js-->
<Avatar src={icon} size="large" />
```
- and now import image location for icon  like this
```jsx
//Navbar.js
import icon from '../images/cryptocurrency.png';
```
**19. let's import this navigation bar into our App.js so that we can display it right here(App.js)**  

- components  from the components, folder looks like  this
```jsx
 import Navbar from './components/Navbar';
```
it's fine for one line or two lines or even three lines but later on you're going to have more components here it's not going to be just snap navbar and your code would look like this

```jsx
import Navbar from './components/Navbar';
import Navbar from './components/Navbar';
import Navbar from './components/Navbar';
import Navbar from './components/Navbar';
import Navbar from './components/Navbar';
import Navbar from './components/Navbar';
import Navbar from './components/Navbar';
import Navbar from './components/Navbar';
import Navbar from './components/Navbar';
import Navbar from './components/Navbar';
```
so on....

- That's definitely not efficient or good-looking you're cluttering your view ,so I'm going to show you a little trick
- that's going to allow you to import all the components in one line
- to do that we can create a new file inside the 'components' folder called "index.js" inside here you can import this like import then curly braces....like this
```jsx
//index.js(component)
import { default as Navbar } from './Navbar';
```
this one line is going to allow us to import navbar in a different way


if we go to again App.js you no longer have to do it like this what you can do is like this 

```jsx
//index.js(src)
 import { Navbar } from './components';
```
Now add more like this

```jsx
//index.js (component)
 export { Navbar, Layout, Footer } from './components';
```

put navbar in curly braces and then  simply say dot slash components and now  all the components that you export  from here  are going to be importable like this  now bar we're gonna have for example a  layout  we're going to have footer  this seems really meaningful import  navbar layout and footer from components  ,and it's also in one line so that's a  cool little trick that you can use in  your React applications




**20.We are gonna export from index.js(component) to import app.js.Now we have to install " react router dom "**

for this do like this 

go to your app.js and open terminal and type
```text
 npm install react-router-dom
```
if your try to start npm start you might be faced an issue so for that you have to do 

go to your app.js and import this 

```jsx
//app.js
import { Switch, Route, Link } from 'react-router-dom';
```

Now so to be able to use links and other  things you need to wrap our app with the  router  so right inside here we can add the  router component ,and you need to put the app component inside it then that's going to look  something like this

```jsx
ReactDOM.render(
  <React.StrictMode>
    <Router>
        <App />
    </Router>,
      document.getElementById('root')
      );
```

Then just do open app.js and open terminal 
```text
npm start
```
