# Learn Node.js by Building 6 Projects
This is the code repository for [Learn Node.js by Building 6 Projects](https://www.packtpub.com/web-development/learn-nodejs-building-6-projects?utm_source=github&utm_medium=repository&utm_campaign=9781788293631), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.
##Instructions and Navigations
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
http.createServer(function(req, res) {
  var uri = url.parse(req.url).pathname;
  var fileName = path.join(process.cwd(), unescape(uri));
  console.log('Loading'+uri);
  var stats;
});
```

With its event-driven architecture and efficient web services capabilities, more and more companies are building their entire infrastructure around Node.js. Node has become a de facto part of web development that any serious developer needs to master.

This book includes six Node.js projects that gradually increase in complexity. You'll start by building a simple web server and create a basic website. You will then move to create the login system, blog system, chat system, and e-learning system.

By creating and following the example projects in this book, you’ll improve your Node.js skills through practical working projects, and you'll learn how to use Node.js with many other useful technologies, such as ExpressJS, Kickstart, and Heroku.

## Related Products
* [Learning Node.js Development](https://www.packtpub.com/web-development/learning-nodejs-development?utm_source=github&utm_medium=repository&utm_campaign=9781788395540)

* [Mastering Node.js - Second Edition](https://www.packtpub.com/web-development/mastering-nodejs-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781785888960)

* [Advanced Node.js Development](https://www.packtpub.com/web-development/advanced-nodejs-development?utm_source=github&utm_medium=repository&utm_campaign=9781788393935)
