backend project week
=======

# Directions
* Create a single repository on your team leaders GitHub account
 * In the repository settings add all the team memebers as Collaborators
* Create npm scripts (in your package.json) for travis and heroku
 * start script should run your server
 * test script should run mocha
 * lint script should run eslint
* Create two heroku apps linked together in a heroku pipeline
 * have them track pull request to the staging and master branches of your project repository
* Have your team leader enable travis for the project
  * Include the **.travis.yml** from this repository in your project week repository
* Create a **README.md** file to document the project purpose and api routes
* Include the **.eslintignore** and **.eslintrc** from this repository in your project week repository
* Create a .gitignore file
 * make sure it ignores the **db** directory and **env.sh** files
* Create these directories to organize your code: 
 * db - use the command `mongod --dbpath ./db` to start mongod using this directory
 * lib
 * model
 * controller
 * route
 * test
