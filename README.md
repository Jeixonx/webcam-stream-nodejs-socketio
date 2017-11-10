# exp-stream-nodejs-socketio

Streaming webcam via websocket using Node.js and soccket.io


To get started with developing using the Socket.IO, you need to have Node and npm (node package manager) installed. If you do not have these, head over to Node setup to install node on your local system. Confirm that node and npm are installed by running the following commands in your terminal.
```
node --version
npm --version
```
You should get an output similar to −
```
v5.0.0
3.5.2
```

we need to install Express and Socket.IO. To install these and save them to package.json file, enter the following command in your terminal, into the project directory.
```
npm install --save express socket.io
```
One final thing is that we should keep restarting the server. When we make changes, we will need a tool called nodemon. To install nodemon, open your terminal and enter the following command −
```
npm install -g nodemon
```
Whenever you need to start the server, instead of using the node app.js use, nodemon app.js. This will ensure that you do not need to restart the server whenever you change a file. It speeds up the development process.
