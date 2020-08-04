# react-app-test
To test the deployement of react app in github pages

## The deployed react app link : https://rosnikv.github.io/react-app-test/


### Step wise (Followed this link - readme file: https://github.com/gitname/react-gh-pages )

1. Created a github repository name **react-app-test""
2. Set up react and then install a basic app : ```npx create-react-app my-app```
3. ``cd my-app``
4. ```npm install gh-pages --save-dev```
5. Add properties in **package.json** file "homepage": "https://rosnikv.github.io/react-app-test/"
6. Add in **package.json** existing *'scripts'* property

```
  "scripts": {
  //...
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
}
```
7. In the my-app directory : ```git init ```
8. ``` git remote add origin https://github.com/rosnikv/react-app-test.git ```
9. To generate the production build app, deploy the react app : ``` npm run deploy ```
10. Now the app is deployed and you can see it in the initial link added in **package.json** *homepage* property : https://rosnikv.github.io/react-app-test/
11. Also, to add the source code to github repo follow these : ```git add . ```, ``` git commit -m "commit message"```, ``` git push origin master``` 

## Your first react app in the github page is ready !
