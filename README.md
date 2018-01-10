# Auth0 Sample Showcase of Centralised Login

[Auth0](https://auth0.com) is an authentication broker that supports social identity providers as well as enterprise identity providers such as Active Directory, LDAP, Google Apps, Salesforce and databases.

Auth0's Centralised Login Page is the most secure way to easily authenticate users for your applications. The Centralised Login Page is easily customizable right from the [Dashboard](https://manage.auth0.com/#/login_page). By default, the Hosted Login Page uses Auth0's Lock Widget to authenticate users, but the code of the Hosted Login Page can be customized to replace Lock with the Lock Passwordless widget, or an entirely custom UI can be built in its place, using the Auth0.js SDK for authentication which this repository contains a sample UI.

Sample project to demostrate [auth0.js](https://github.com/auth0/auth0.js) 

* Login with social connections e.g facebook, twitter, google
* Login with database connection
* Reset Password
* Signup with first name, last name, email, password
* Signup and login with email passwordless
* Signup and login with mobile passwordless

## How to set up Auth0 Centralised Login Page.
* Copy the html contents of the [centralised-page](https://github.com/vikasjayaram/auth0-centralised-login/tree/master/centralised-page) folder into the [Login Page](https://manage.auth0.com/#/login_page)
* Click Save
* Check the Preview tab to see the page load correctly.

## Further Reading
* More elaborate details about the Hosted Page can be found [here](https://auth0.com/docs/hosted-pages/login#about-the-hosted-login-page) 

## Login

![Login](https://github.com/vikasjayaram/auth0-samples/blob/master/screenshots/auth0_custom_ui_login.png)

## Signup

![Signup](https://github.com/vikasjayaram/auth0-samples/blob/master/screenshots/auth0_custom_ui_signup.png)
