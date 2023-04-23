# Create Login Form and Register Form with Node.js and Passport.js and Bootstrap

Learn the things you need to know about user login and authentication and secure all user's passwords by hashing them.

## To start with the files

Open your Terminal and type the following commands as you enter them

```cmd
cd Desktop
mkdir login-register-form
cd login-register-form
npm init -y
npm i express ejs
npm i --save-dev nodemon dotenv
code .
```

### Go to the package.json and add the following to the scripts

```json
"devStart": "nodemon server.js"
```

Then create a **server.js** file inside of the current directory

### Inside of the server.js, type the following code

```js
const express = require('express')
const app = express()

app.listen(3000, () => console.log('Server started at port 3000'))
```

### Lastly, go to your browser and enter this link

```
http://localhost:3000
```

### Go back to terminal and run this commad

```cmd
npm run devStart
```

And there you have the starter file.

Based from the tutorial of [Wev Dev Simplified](https://www.youtube.com/watch?v=-RCnNyD0L-s&list=PLZlA0Gpn_vH9yI1hwDVzWqu5sAfajcsBQ) and here is the [original source code](https://github.com/WebDevSimplified/Nodejs-Passport-Login.git)
