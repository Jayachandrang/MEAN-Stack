# MEAN-Stack
MEAN Stack architecture

Firstly, the client makes a request which is processed by the AngularJS
After that, the request moves to NodeJS which will parse the request.
ExpressJs will make calls to MongoDB to get or set data.
MongoDB will retrieve the requested data and return that request to the Express JS
NodeJS will return the request to the client.
At the client side, AngularJS to display the result fetched from MongoDB.
