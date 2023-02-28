# PROJECT 3: MERN STACK IMPLEMENTATION
## Step 1 - Backend Configuration
### Update ubuntu
- `sudo apt update`
### Upgrade ubuntu
- `sudo apt upgrade`
### Get the location of Node.js software from Ubuntu repositories
- `curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -`
### Install Node.js on the server
- `sudo apt-get install -y nodejs`
### Verify the version of node and npm installed
- `node -v`
- `npm -v `
![Node&npm](images/node%26npm-installed.jpg)
## Application Code Setup
### Create new directory for the To-Do project
- `mkdir Todo`
- `cd Todo`
### initialise your project, so that a new file named package.json will be created.
- `npm init`
![pakage json fie](images/package-jason-file.jpg)

## Install ExpressJS
- `npm install express`
![ExpressJS Installation](images/expressjs-install.jpg)

### create a file index.js
- `touch index.js`
### Run `ls` to confirm that your index.js file is successfully created
### Install the dotenv module
- `npm install dotenv`
![dotenv module](images/dotenv-module.jpg)

### Open the index.js file
- `vim index.js`
![index.js code](images/index.js-code.jpg)
### Use `:w` to save in vim and use `:qa` to exit vim

### start our server to see if it works 
- `node index.js`
![Running server](images/index.js-code.jpg)
### Checking from the web
![Checking on the web](images/checking-web.jpg)

### Create a folder "route" and cd in to it and create "api.js" file
![route directory](images/route-directory.jpg)
### Install mongoose
![mongoose](images/mongoose.jpg)

### Create a new folder - models
- `mkdir models && cd models && touch todo.js`

## Create a MongoDB database and collection inside mLab
### Create a file in your Todo directory and name it .env.
- `touch .env`
- `vi .env`
### Add the connection string to access the database in it, just as below:
- `DB = 'mongodb+srv://<username>:<password>@<network-address>/<dbname>?retryWrites=true&w=majority'`
![DB Connection String](images/DB_connection_string.jpg)









### Side Study

[Database Management Systems (DBMS) exist and what each type is more suitable for](https://www.alooma.com/blog/types-of-modern-databases)

[Datastream](https://cloud.google.com/datastream)

[Web Application Frameworks](https://en.wikipedia.org/wiki/Web_framework)
[Basic JavaScript syntax](https://www.w3schools.com/js/js_intro.asp)
[REST API Tutorial](https://restfulapi.net/)
[What is RESTful API?](https://aws.amazon.com/what-is/restful-api/)
[Basic Syntax and Properties of CSS](https://www.w3schools.com/css/css_intro.asp)






