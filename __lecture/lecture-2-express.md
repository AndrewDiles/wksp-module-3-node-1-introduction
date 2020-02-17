# 3.1.2 - Module Spotlight: Express

<img src='./assets/express.png' style="min-width: 50%;" />

---

## One of the most important node modules

It removes _a lot_ of the complexity around creating and maintaining a server.

---

### Example

This will give us a barebones server that we can _GET_ content. 

// below is written into a js file
```js
const express = require('express');

const app = express();
//always gets request and response
//app.get('/', function(req,res){res.send('hello');})
app.get('/', (req, res) => {
    res.send('hello');
});
// this sets the port that the site is using
app.listen(4000);
```

---

_Let's create a server right now!_
// to run, in terminal, type: node index.js                (presuming that is the name you have this is)
//in browser, go to localhost.4000 in browser
---

Let's explore the workshop repository together.

---