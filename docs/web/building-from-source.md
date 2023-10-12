# Building From Source
Calzone Web is based on [ExpressJS](http://expressjs.com/) in [NodeJS](https://nodejs.org/). To start, make sure you have installed the [latest current](https://nodejs.org/en/download/current) build of NodeJS. You can verify it is installed and ready to go by typing `node version` into your prefered terminal.

Next, download or clone a copy of the [web client's Github Repo](https://github.com/TailTwistStudios/Project-Calzone-Web).

This project requires some dependencies, to install them; open a terminal in the project folder and use the command `npm install` to download and install all required packages.

**Optional:** If you're planning to do development work on the project, we reccommend using Nodemon. Nodemon is a watcher program that automatically runs the web server and restarts it every time you save a file. It will not install automatically, manually install it globally on your machine (instead of in-project) using `npm install -g nodemon`.

**Note:** Currently the project uses MongoDB to reliably store and access some userdata, however it's currently up for debate whether or not we should continue using MongoDB. Much of the current implementation is incomplete and prone to breaking, and might be scrapped. So for now; just install [MongoDB Community](https://www.mongodb.com/try/download/community) and check in later to see if we've moved to a different solution. There's no further setup or configuration needed because there is no further implementation of Mongo in the project beyond the minimum viable product.

Now that all prerequisites are installed, you can run `node app.js` in the project directory to run the webserver. Once up and running it will immediately begin listening and set up a web interface at `localhost:3000`.
