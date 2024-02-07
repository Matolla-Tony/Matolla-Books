setup

install node

npm init -y #default all parameters to yes

install packages
express -server
ejs - templating language
express-ejs-layouts -to create layout files for all HTML
mongoDB
body-parser makes it easy to access input elements from our server
dotenv - enables loading of environment variable
npm i express ejs express-ejs-layouts mongoose body-parser

install development dependency
npm i --save-dev nodemon (save as a development dependency)
npm i --save-dev dotenv
automatically refreshes our server when we make changes

run
npm run devStart

MVC Structure
