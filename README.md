#Namaste-React🏆🚀 
#Let's Ignite Our App😎

#git commands
#git init
#git branch -M main
#git config --global user.email "laxmipriyapradhan374@gmail.com"
#git config --global user.name "laxmipriyapradhan"
#git add .
#git commit -m "meesage"
#git remote add origin https://github.com/laxmipriyapardhan/Namste-React.git
#git push origin main
#git status

#there are several commands are there to ignite our app 
#those are written below
#1. npm init - package.json file automatically generate which is the configuration of our npm 
#2.npm install -D parcel - package-Lock.json & node_modules for bundling our app
#3.gitignore /node_modules
/dist
.parcel-cache
#4.npx parcel index.html - hosted our app to the server
#5.CDN links remove and install the React & React-DOM
-> npm install react
->npm install react-dom
import React from 'react';
import ReactDOM from 'react-dom/client';
and add the <script type="module" src="./App.js"> </script> in your index.html
#6 load the https then run the cmd
->npx parcel index.html --https
#7 for build the production app the run the cmd
npx parcel build index.html
remove the entry point from package.json
we can regenerate the gitignore files that's why we don't need to push this files to github repo


#parcel 
-Dev build 
- Local server
- HMR- Hot module replacement (save then auto refresh the page in the browser)
- file watching algo written in C++
- faster builds - Relaible caching
- Diff Dev and prod bundles
- Image optimazation
- Minification
- Bundling
- Compress
-Consistent Hashing
- Code splitting
- differential bundling - support older browser
- Diagostic
- Error handling
- HTTps
- Tree shaking - remove unsed code


