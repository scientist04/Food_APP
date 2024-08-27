# Episode - 01

  - Printing Hellow World! using HTML
  - Printing Hellow World! using JavaScript

  - Configuring Project to use React using CDN links
  - Printing Hellow World! using React

  - Library vs Framework


# Episode - 02

  - Creating and configuring Git Repository
  - NPM
  -------- npm init - package.json is created
  - package.json - COnfiguration file for npm (maintains the versions of our dependencies, can maintains the 
    exact version or cannot be using 'carat(minor upgrade)' or 'tilda(major upgrade)').
  - package-lock.json - it keeps tracks of exact versions that is being installed
  --------- npm install -D parcel
  - Dependency vs Dev-dependency
  - node_modules - contains all the code of packages (behave as a database for node packages).
  - gitignore - the file/folder which we don't want to push on github (files that are can be re-generated).
  --------- npx parcel index.html
  --------- npm install react
  --------- npm install react-dom
  # Parcel 
    - Dev Build
    - it create local server for us or it host our app to the server
    - parcel is automatically refreshes our page, also this is called HMR (Hot Module Replacement).
    - parcel uses file watching algorithm which is written in c++
    - parcel is giving faster development experience because it is also doing caching
    - The most expensive thing in our web-browser is to load images in our page and parcel basically do image
      optimization for us as well.
    - If we create a production build, it will minify our file also (minification)
    - Parcel bundle all the file for us (Bundling)
    - Compresses the file
    - Consistent Hashing
    - Code Splitting
    - Differential Bundling - to support older browsers
    - Diagnostics - Gives Beautiful Errors in Window and in developer console
    - Error Handling
    - HTTPS
    - Tree shaking algorithm - remove unused code
    - Different dev and product bundles

  - parcel-cache and dist folder can be regenerated.
  - to make our app compatible for the older versions of browsers for that we use "browserlist"








