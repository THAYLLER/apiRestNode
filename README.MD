# HapiJS Dog API

study using api rest nodejs and hapi.js

## Installation and Running the App

after downloading the api to your computer run: 

```bash
npm install
```
to install the project dependencies, and then enter the project folder and run

```bash
node start
```

The app will be served at `localhost:3000`.

## Available Routes

#### **POST** `/dogs`
* Accepts `name`, `breed`, `age` and `image` to create a dog.

#### **GET** `/dogs`
* Returns all dogs in the database.

#### **GET** `/dogs/{id}`
* Returns the detail of a dog in the database.

#### **PUT** `/dogs/{id}`
* Updates a dog details.

#### **DELETE** `/dogs/{id}`
* Deletes a dog.

 
## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, amont others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
* Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
* Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
