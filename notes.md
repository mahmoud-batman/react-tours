## install SASS :

> npm install node-sass --save

- **rename the `index.css` file into `index.scss`**
- **import `index.scss` in index.js**

- **do the same as prev for App.js and `App.css` into `App.scss`**

- **put the `img` folder in the public folder**

## Google Font :

- choose the font

  - add the link in `index.html`

    > \<Link href="https://fonts" rel="stylesheet" />

    > add the font family in the index.scss file

## Font Awesome:

- **copy the CDN add the link in `index.html`**

# Deployment on `Netlify` :

## 1 ) Drag and Drop :

1- Go to netlify.com

2- npm run build

3- Drag and Drop the build folder

## 2 ) Continous Deployment with `Git` :

**1- Git :**

- Initialize the local repo `.git`

  > git init  
  > (`first time only`)

* Add files to Staging Area

  > git add .

* Commit Changes

  > git commit -m

  - \- m : message

* create a new repo on github then get the following command

  > git remote add origin url
  > (`first time only`)

- Push changes to remote repo
  > git push -u origin master

**your project is ready on github**

**2- Netlify :**

- new site from git and follow the steps
- when you make changes on github
