##  NODEJS BLOG API

### INSTALLATION STEPS


1- Start NodeJs Project

```shell
npm init -y
```

2- Installations of express
```shell
npm i express
```

3- We add our startup script to our package.json file
```shell
"scripts": {
  "serve": "node Index.js"
}
```

4- Install Nodemon (It automatically detects the changes we make to our files and restarts the server for us.)
```shell
npm i nodemon -D
```
and then we add our script to our package.json file
```shell
"scripts": {
  "dev": "nodemon Index.js"
}
```

5- We install our dependency for our mongo database connection
```shell
npm i mongoose
```

6- For MongoDB usage go to below url

```shell
https://www.mongodb.com/docs/
```
