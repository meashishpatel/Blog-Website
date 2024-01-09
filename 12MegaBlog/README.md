# My Space

# Write the following commands in the command line
```
npm create vite@latest
```
> Project name: 12MegaBlog
```
cd 12{hit tab}
npm install
npm i redux
npm i @reduxjs/toolkit react-redux react-router-dom appwrite @tinymce/tinymce-react html-react-parser react-hook-form
```

# Create enviroment variables
> Make a file in the root named as .env
* Add that file to git ignore from branching option in VS code and and right click and then select add to git ignore
* Make another file named as .env.sample to ship that on git
* To get the access of .env varialbles in app.jsx use
> console.log(process.env.REACT_APP_APPWRITE_URL)
> NOTE: The variable name must start with REACT_APP_VARIABLE and for vite apps it must be VITE_APPWRITE_URL 
* To get the access of .env varialbles in app.jsx use console.log(import.meta.env.VITE_APPWRITE_URL)

