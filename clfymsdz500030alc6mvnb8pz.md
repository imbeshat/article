---
title: "How to create the first express app"
datePublished: Sat Apr 01 2023 23:55:07 GMT+0000 (Coordinated Universal Time)
cuid: clfymsdz500030alc6mvnb8pz
slug: how-to-create-the-first-express-app
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1680392084447/d6831a71-4d97-4430-a98f-4a22e6dad824.png
tags: express, nodejs, backend, learncodeonline, iwritecode

---

People might think that creating an express app is a tedious task. But, my friend let me tell you that creating an express app is the easiest thing we can do. In this article, we will learn about Express and slowly strive towards creating the first Express app.

## What is Express?

Before knowing how to create the first express app let us understand what express is.

Express.js, or simply Express, is a back-end web application framework for building web servers and RESTful APIs with Node.js. This framework provides a robust set of features for web and mobile applications.

As by the definition of express, we now know that this framework requires Node.js. So, we should have Node installed in our system.

## Creating the Express app

Assuming that we already have Node.js installed in our system. Let us move towards the steps for creating our first express app.

To begin with first, we should create a new directory by opening the terminal and by using the following command:

```bash
mkdir first-express-app
```

After creating the directory, we have to move into the directory by using the following command:

```bash
cd first-express-app
```

Now we have to initialize the directory or we can say that we have to create a package.json file for the application. We do the same by using the following command:

```bash
npm init
```

If we want to use the default value we use `npm init -y`. If we want to use our value then we use `npm init` and after that, we provide the details.

Next, we have to install Express. To do so we use the following command:

```bash
npm install express
```

Now, after installing Express, we have to create our first server/express app. And for creating the server/express app we have to create a new file "index.js" and use the following code:

```javascript
const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Hello World!')
})

app.listen(port, () => {
  console.log(`Example app listening on port ${port}`)
})
```

In the code above, we first import the Express module and create an instance of the app. Then we define the port number on which we want our app or server to run. We then define a route for the root URL ("/") and send a "Hello World!" message to the client.

Finally, we start the server by calling the "listen" method and passing in the port number (3000) that the server should listen on.

And to run the app we use the following command:

```bash
node index.js
```

The above command will start the server and we can open the same by navigating to the URL `http://localhost:3000/`. After running this we will see "Hello World!" on the web page.

## Conclusion

That's all it takes to create the first express app. It's no rocket science, just have to follow basic steps. In this article, we understood what Express is and how to create our first express app.

Thanks for reading 🙂.