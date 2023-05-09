# Dalle-clone
***

## 1. Setup

> **Structuring of client folder**  

Create and cd to client folder  and initialise a vite app to the current directory ' client '. A structure for the client directory will be generated.

```
npm create vite@latest ./
```
<br />
<br />
  
> **Install and Initiate the tailwindcss**

Because we are using vite, check the documentation of talwindcss and find out how to install it with vite. [Documentation](https://tailwindcss.com/docs/guides/vite)    
[Note: __You must be in the client directory__ ] 

```
npm i -D tailwindcss postcss autoprefixer
```
and then run the command to create a config file for talwindcss for website.  
[Note: __Before initialising, add the assets and constants by following [this](assets-from-tutorial/tutorial-assets.md)__ ]  


```
npx tailwindcss init -p  
```   
<br />
<br />
  
> **Set up to view on vite app**  

[Note: __First of all, change the tailwindcss config file by following [this](assets-from-tutorial/tutorial-assets.md)__ ]   
Now, install an extension `es7+ React/React-Native snippets` on vscode. Clear everything on `app.jsx` and type-enter  
```
rafce 
```
to create a boilerplate code for react and add a h1 tag with the following className and write `Hello World!` given in the tailwind documentation/site. (for vite)  
```
className="text-3xl font-bold underline"
```

Install ' file-saver ' 
```
npm i file-saver
```  
and run the vite application.
```
npm run dev
```  
<br />
and import inter font in the html document as a stylesheet in the head element, to use it and check if everything is running properly.   
href="https://rsms.me/inter/inter.css"  

<br />
<br />
<br />  

  
> **Set up the pages and create a route of it in the App component**  

First, install the react-router and re-run the vite app, and import { BrowserRouter, Link, Route, Routes } from ' react-router-dom ', as well as the logo from assets to the app component.
```
npm i react-router-dom
```  

<br />
Secondly, create Home and CreatePost page inside the pages dir and also index.js to export those pages to the app component. Then import Home and CreatePost in to the app component and route the pages. Use tailwind class to do the basic design of the header.











***
## 2. Do the Homo page

* import useState, useEffect from react in addition to React.
* Create component folder and add Card.jsx, FormField.jsx, Loader.jsx.
* Create functional component using ' rafce ' on Card and FormField, but add the Loader from the gist [here](assets-from-tutorial/tutorial-assets.md) !
* Create index.js under the same directory to export the jsx files.
* Then, setup the Home page, see commits.



