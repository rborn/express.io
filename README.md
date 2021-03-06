![express.io](http://cdn.techpines.io/express.io-black.png)

realtime-web framework for node.js

```coffeescript
express.io = express + socket.io
```

## Simple App Setup

Here is the canonical express.io example.

```javascript
app = require('express.io')()
app.http().io()

//build your realtime-web app

app.listen(7076)
```

## Upgrade your existing Express apps

First install:

```bash
npm install express.io
```

Then, simply replace this line of code

```javascript
require('express')
```

with this line of code

```javascript
require('express.io')
```

Your app should run just the same as before!  Express.io is designed to be a superset of Express and Socket.io.  An easy to use drop-in replacement that makes it simple to get started with the realtime-web.


## Examples


__All of these examples work.__  I repeat, __they all work__.  Express.io is a very simple framework that allows you to build incredibly complex realtime apps with very little code.

[All Examples](https://github.com/techpines/express.io/tree/master/examples#readme)

Or view them bite size:

* [Simple HTTP + IO Setup](https://github.com/techpines/express.io/tree/master/examples#simple-http--io-setup)
* [Simple HTTPS + IO Setup](https://github.com/techpines/express.io/tree/master/examples#simple-https--io-setup)
* [Routing](https://github.com/techpines/express.io/tree/master/examples#routing)
* [Route Forwarding](https://github.com/techpines/express.io/tree/master/examples#route-forwarding)
* [Broadcasting](https://github.com/techpines/express.io/tree/master/examples#broadcasting)
* [Sessions](https://github.com/techpines/express.io/tree/master/examples#sessions)
* [Rooms](https://github.com/techpines/express.io/tree/master/examples#rooms)
* [Acknowledgements](https://github.com/techpines/express.io/tree/master/examples#acknowledgements)
* [Realtime Canvas](https://github.com/techpines/express.io/tree/master/examples#realtime-canvas)
* [Scaling with Redis](https://github.com/techpines/express.io/tree/master/examples#scaling-with-redis)

To run the examples from git, do the following:

```js
git clone https://github.com/techpines/express.io
cd express.io/examples
npm install
```

Then you'll be ready to run the example code with a simple:

```
node app.js
```

## API Reference

This should help you get a birds eye view of the __express.io__ architecture.  Simple and lean.  Reuse your express and socket.io knowledge.

[API Reference](https://github.com/techpines/express.io/tree/master/lib#readme)

Here are all the wonderful __express.io__ objects!

* [ExpressIO](https://github.com/techpines/express.io/tree/master/lib#expressio)
* [ExpressApp](https://github.com/techpines/express.io/tree/master/lib#expressapp)
* [AppIO](https://github.com/techpines/express.io/tree/master/lib#appio)
* [SocketRequest](https://github.com/techpines/express.io/tree/master/lib#socketrequest)
* [RequestIO](https://github.com/techpines/express.io/tree/master/lib#requestio)

## FAQ

Have frequent questions, we have frequent answers.

[Check here](https://github.com/techpines/express.io/tree/master/docs/faq.md).

## License
It's free! Party with the MIT!

Copyright (c) 2012 Tech Pines LLC, Brad Carleton 

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
