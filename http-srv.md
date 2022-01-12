# http-srv
This package makes using the built in http module easy as pie so you can create a single page web app in a few minutes!
# Usage
simply put index.js into a file in your project and import it with
```js
const httpsrv = require("./file name.js")
```
# Functions
http-srv only has two main functions that would be needed for a simple webserver

these functions look like express' so its fairly easy to understand

send & sendfile

```js
httpsrv.send("content", port)

httpsrv.send("Hello World", 3000)
```

```js
httpsrv.sendfile("file.ext", port)

httpsrv.sendfile("index.html", 3000)

httpsrv.sendfile("somedir/index.html", 300)
```
