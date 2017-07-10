# ReactJS Socket.io Chat Application

/**
 * Author: Thien Le
 * Github: http://github.com/thienle75
 * 
 */
## Running it

First, grab the dependencies:

    npm install

Build the applicaiton
	
	npm run build

Then run the app like so:

    npm start

And navigate to `localhost:3000` and chat !

Chat Functionality
1. Guest user name assign when website load
2. Notify other clients that a new user has joined
3. Validate a user's name change, and broadcast it on success
4. Clean up when a user leaves, and broadcast it to other users.