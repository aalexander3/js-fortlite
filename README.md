## JS Fortlite

### Getting Started
You will be using the json-server package to mock an external API. You can make the same RESTful requests to this server that you would to any API. If you haven't yet, install json-server.

`npm install -g json-server`

Then run the server with:

`json-server --watch db.json`

This will serve your code on http://localhost:3000.

### A Game
A game object will include a few different attributes: user, points, resources, structures_built, time, and health. Each of these attributes can be updated as the game progresses.

```{
"user": "myName",
"points": 10,
"resources": 3,
"structures_built": 2,
"time": 0,
"health": 2
}
```
