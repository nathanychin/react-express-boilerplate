# Cheat sheet for connecting React and Express

``` bash
# Run npm init
npm init
# change entry point to server.js

# Install express
npm install express concurrently

# Install nodemon
npm install nodemon --save-dev

# In package.json in "scripts"
## add "client-install": "cd client && npm install",
## add "server": "nodemon server.js",
## add "client": "cd client && npm start",
## add "dev": "concurrently \"npm run server\" \"npm run client\""

# Make new file called server.js
## Backend code goes here

# Install create-react-app
npm install -g create-react-app

# Run create-react-app client
create-react-app

# In client package.json add "proxy": "http://localhost:5000" at the bottom

# To update npm dependancies
npm run client-install

# Run server only
npm run server

# Run client only
npm run client

# Run both
npm run dev

```
