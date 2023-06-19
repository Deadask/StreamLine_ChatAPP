I followed the tutorial for the chat app here:
https://www.youtube.com/watch?v=otaQKODEUFs

## Installation Guide

rename .env_Change files to .env

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

to install dependencies open commandline on the directory
```command line
cd server
yarn
cd ..
cd public
yarn
```

  ///////////////////////////////
 ////// Starting the App ///////
///////////////////////////////

For Frontend.
```command line
cd public
yarn start
```
For Backend.

Open another command line in folder, Also make sure mongodb is running in background.
```command line
cd server
yarn start
```

localhost:\3000 should automatically open on your browser.
