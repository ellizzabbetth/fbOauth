# node-ionic-jwt
Ionic authentication using JWT and nodejs.

An Ionic authentication example using JWT implemented on nodejs server.
**[Blog Post](http://blog.grossman.io/ionic-jwt-auth-with-facebook-using-nodejs-part-1/)**
#Installation
- clone repository
- enter server directory and ```npm install```
- rename .env.example file to .env
- add your fb app credentials inside .env file
- run server with ```npm start```
- enter ionic directory
- set your facebook auth credential values for ```clientId``` and ```url``` in ```www/js/app.js```
- run ```ionic serve```


Configure Server:
http://stackoverflow.com/questions/20796714/what-is-the-way-to-start-mongo-db-from-windows-7-64-bit

Start Server:
Open first cli with cmd

cd to C:\Program Files\MongoDB\Server\3.4\bin

enter command MongoDB

Open second cli with command
cd to C:\AngularJS\node-ionic-jwt\server

npm start
