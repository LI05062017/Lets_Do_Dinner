Lets_Do_Dinner
This project was done between two classmates, and myself while in Big Sky Code Academy. Our inspiration was from the FoodToFork API, and we each worked on different components of the project.

My contributions to this projct are in Header.js, Main.js, Menu.js, Home.js TopRated Components, and in Trending Components.

1) Make sure mongo DB is runnining
`sudo mongod`

2) Update the line in `server/server.js` to use your DB of choice
`mongoose.connect('mongodb://localhost/__YOUR_DB__')`

3) Install Client packages
`npm run install:client`

4) Install Server packages
`npm run install:server`

__Tip__
You can run both the previous steps in one command:
`npm run install:client && npm run install:server`

5) Start Client
`npm run start:client`

6) Start Server
`npm run start:server`

Browser is loaded at `localhost:3000` and server api is located at `localhost:3001`
