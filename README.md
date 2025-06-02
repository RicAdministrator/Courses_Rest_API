// open new terminal, make sure you are in root dir
// install dependencies using command below
npm i express // restful api framework
npm i -g nodemon // install nodemon globally
npm i joi // used to validate req.body during insert/post and update/put

// run in terminal to set the port
set PORT=5000 // windows 
export PORT=5000 // mac

node index.js // if code is updated, run this command again
nodemon index.js // if code is updated, no need to re-run command