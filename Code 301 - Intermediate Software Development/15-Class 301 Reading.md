# Reading

## What is OAuth

What is OAuth? OAuth is a delegated authorization framework for REST/APIs
Give an example of what using OAuth would look like. a user's Strava account can access their Garmin Connect account without needing to share their Garmin username and password with Strava. 
How does OAuth work? What are the steps that it takes to authenticate the user?The resource owner authenticates and authorizes the resource access request from the application, and the authorize endpoint returns an authorization grant to the client
What is OpenID? OpenID is an open standard and decentralized authentication protocol promoted by the non-profit OpenID Foundation.

## Authorization and Authentication flows

What is the difference between authorization and authentication? authentication is the process of verifying who someone is, whereas authorization is the process of verifying what specific applications, files, and data a user has access to.
What is Authorization Code Flow? enables a client application to obtain authorized access to protected resources like web APIs. 
What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)? is an OpenId Connect flow specifically designed to authenticate native or mobile application users.
What is Implicit Flow with Form Post? uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates
What is Client Credentials Flow?  permissions are granted directly to the application itself by an administrator
What is Device Authorization Flow? contains two different paths; one occurs on the device requesting authorization and the other occurs in a browser
What is Resource Owner Password Flow? allows exchanging the username and password of a user for an access token and, optionally, a refresh token