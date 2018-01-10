# Auth0 Custom UI

[Auth0](https://auth0.com) is an authentication broker that supports social identity providers as well as enterprise identity providers such as Active Directory, LDAP, Google Apps, Salesforce and databases.

Sample project to demostrate [auth0.js](https://github.com/auth0/auth0.js) 

* Login with social connections e.g facebook, twitter, google
* Login with database connection
* Reset Password
* Signup with first name, last name, email, password
* Signup and login with email passwordless
* Signup and login with mobile passwordless

## Running locally

To run it locally:

* Make `auth0Hosted = false` for local testing in index.js
* Populate the config object

```bash
    config = {
      auth0Domain: 'YOUR_AUTH0_DOMAIN',
      clientID: 'YOUR_CLIENT_ID',
      callbackURL: 'YOUR_CALLBACK_URL',
      responseType: 'token id_token',
      dict: {
        signin: {
          title: 'Welcome to Auth0'
        }
      }
    };
```

```bash
$ npm install serve -g
$ serve .
```


## Login

![Login](https://github.com/vikasjayaram/auth0-samples/blob/master/screenshots/auth0_custom_ui_login.png)

## Signup

![Signup](https://github.com/vikasjayaram/auth0-samples/blob/master/screenshots/auth0_custom_ui_signup.png)
