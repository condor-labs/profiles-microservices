# Collection of Microservices for external Logging  And others 🚀

We want to build an app to share with our co-workers inside an organization, and in the process let to the comunity tools for create similar things.

## Tech stack
- ReactJS 
- Node.JS 
- MongoDB
- OAuth Outlook 

## Connection to Outlook 

Since we need to get users from Outlook Contacts, we should develop a tool using a express server, apiGateway or whatever to authenticate the user and save the user information in a Users's mongoDB Collection.

This Endpoint/API/service should be customizable for anyone who wants to use this implementation

![image](https://user-images.githubusercontent.com/42990423/95476751-2f8f8a00-094d-11eb-839a-7d3310af2484.png)


Requeriments:

* Connect with Microsoft using a OAuth2 Token given by params
* Get the User information
* Store in a MongoDB Collection

# React client for logging with Outlook 

In order to support the Auth2 login with Outlook, we need to create a frontend to interact with Microsoft login, it should:

- Show a welcome page with a call to action to sign in with outlook, this one redirects to the Outlook Sign In.
- A Callback page to receive the token via URL once the user logged in.
- 9 Send token to /auth API :)

## Questions/Answer builder - Backend 

[building]