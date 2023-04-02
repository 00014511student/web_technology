# Student Id: 00014511

# About app

Created is a spendings tracking app where user can create various categories and add his/her spendings with information about name of spending date, amount and some description.

# Steps to run app:

* inside project folder run: npm install
* in order to run app with nodemon run: npm run serve
* in order to run app with node run: node app
  
# Dependencies list:
* express - used as backend framework
* pug - used as view engine
* express validator - used to validate user inputs
* nomdemon - used to auto reload on code change

# Github repository link: 
https://github.com/00014511student/web_technology.git

#   Project Structure

During the project development it was decided to split code logic to different folders in order to keep code clean and for simples code maintenance

* app.js - main js file where app runs
* data - storage of json files that are playing roles of database
* managers - folder of managers that consists general logic. Inside managers folder there is DataManager file which exports class that consists methods to manage data in json files. Methods inluces: getAll, find, insert, update, delete
* public - folder for keeping public files like images, javascript files and style files
* routers - folder for keeping route files of application. Route files: spendings, categories
* validation - files in validation folder export validation rules for storing user data
* views - folder includes all views of application 