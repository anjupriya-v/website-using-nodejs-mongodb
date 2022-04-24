# Website using Node.js and MongoDB

## Tech Used

- Ejs
- Css
- Node.js (Express.js)
- MongoDB (Mongoose)

## Live Demo:
$ https://website-using-nodejs-mongodb.herokuapp.com/

## Database - MongoDB Atlas Database

- Create the account in https://www.mongodb.com/cloud/atlas

- Create the cluster and if you want, you can use free one.

- Create the database and after that, create the collection.

- Inside the database access, create the user.

- you will find connect option after creating cluster, after doing the above operations click the connect option and you will find the db url and set the password and database name in that url

- Go to the root directory in the cloned repo folder

- create .env file

- And write like the following line:

```
DB_URL="YOUR-DB-URL"
HEADER="any-header-key" (your choice eg.sbdfjsd)
``` 

## :point_down:Steps to initialize the project:

- Clone the repository
```
$ git clone https://github.com/anjupriya-v/website-using-nodejs-mongodb.git
```
- Redirect to the cloned repo directory

- Open up the terminal 

- Install the dependencies
```
npm install
``` 
- Start the project 
```
node index
```
