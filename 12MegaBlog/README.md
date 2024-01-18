# My Space

# Write the following commands in the command line
```
npm create vite@latest
```
> Project name: 12MegaBlog
```
cd 12(hit tab)
npm install
npm i redux
npm i @reduxjs/toolkit react-redux react-router-dom appwrite @tinymce/tinymce-react html-react-parser react-hook-form
```

# Create enviroment variables
> Make a file in the root named as .env
* Add that file to git ignore from branching option in VS code and and right click and then select add to git ignore
* Make another file named as .env.sample to ship that on git
* To get the access of .env variables in app.jsx use
> console.log(process.env.REACT_APP_APPWRITE_URL) <br>
> NOTE: The variable name must start with REACT_APP_VARIABLE for react apps and for vite apps it must be VITE_APPWRITE_URL 
### To get the access of .env variables in app.jsx use 
```console.log(import.meta.env.VITE_APPWRITE_URL)```

# Setting up the project
* Go to the website appwrite
* Then create new project
* Go to the settings and then copy Project ID and API Endpoint and paste in the .env file
* ## In Auth settings
    * Go to settings then enable email/password
* ## In Database settings
    * Create database name that as blog hit create
    * Copy and paste database id to the .env file
    * Create collection name that as blog and then paste that in the .env file
    * Go to the settings of the collection id and then in permissions add role and then give every permissions to users
    * Then create attributes of the collection then add keys as title, content, featuredImage, status, userId
    * Go to indexes, create index (index key - status, type - key, attribute - status, )
* ## In storage settings
    * Create bucket, them name that as images.
    * Then copy and paste the bucket id to .env file
    * Give permissions "all users" create, read, update, delete


# Making a service
* Make a folder named as appwrite in src

* ### auth.js file
```javascript
prefer file for the code
```

* ### config.js file
```javascript
prefer file for the code
```