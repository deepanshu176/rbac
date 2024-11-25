# Role Based Access Control (...still in dev mode...)

This is a Role Based Access Control application using Nodejs, Express, Passport Js, etc.
You can use this application as the starting point for whatever project you are going to build which needs authentication and authorization.

For authentication we have only Email & Password option but other authentication options using OAuth/OAuth2.0 like Google, Facebook, Apple, GitHub, etc, can be easily incorporated.

The application is based on the **MVC pattern** i.e. Model View Controller.

**Mongoose** is used as an ORM for MongoDB for storing Users in Database.

**Passport JS** is used for local(email, password) authentication.

The application is _almost_ **production ready**.

---

## To start setting up the project


Step 1: Put your credentials in the .env file.

```bash
PORT=3000
MONGODB_URI=YOUR_MONGODB_URI(example: mongodb://localhost:27017)
DB_NAME=YOUR_DB_NAME
```

Step 2: Install MongoDB (Linux Ubuntu)

See <https://docs.mongodb.com/manual/installation/> for more infos


Step 3: Start the app by

```bash
npm run dev
```





