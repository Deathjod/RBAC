# Role Based Access Control 

This is a Role Based Access Control application using Nodejs, Express, Passport Js, etc.

For authentication we have only Email & Password option but other authentication options using OAuth/OAuth2.0 like Google, Facebook, Apple, GitHub, etc, can be easily incorporated.

The application is based on the **MVC pattern** i.e. Model View Controller.

**Mongoose** is used as an ORM for MongoDB for storing Users in Database.

**Passport JS** is used for local(email, password) authentication.

The application is _almost_ **production ready**.

---

## To start setting up the project

Step 1: Clone the repo

```bash
git clone https://github.com/trulymittal/role-based-access-control
```

Step 2: cd into the cloned repo and run:

```bash
npm install
```

Step 3: Put your credentials in the .env file.

```bash
PORT=3000
MONGODB_URI=YOUR_MONGODB_URI(example: mongodb://localhost:27017)
DB_NAME=YOUR_DB_NAME
```


Step 6: Start the app by

```bash
npm start
```

