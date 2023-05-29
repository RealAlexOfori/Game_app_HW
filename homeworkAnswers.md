
1. What is responsible for defining the routes of the `games` resource?
Answer: The createRouter function within the create_router.js file

2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
Answer: The client is responsible for the frontend and the server is responsible for the backend

3. What are the the responsibilities of server.js?
Answer: It connects the frontend to the database

4. What are the responsibilities of the `gamesRouter`?
Answer: The gamesRouter is a new router created and being passed the gamesCollection

5. What process does the the client (front-end) use to communicate with the server?
Answer: The client uses restful routes for communication

6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs 
Answer: Second argument is an init options object. This allows you to customise and configure the request that is being made 

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
Answer: baseURL

8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?
Answer: It's used to pass information from the server to the database.


