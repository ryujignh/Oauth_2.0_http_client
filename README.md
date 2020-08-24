# Oauth_2.0_http_client

A simple http client for testing Oauth flow.

# How to use

1. Create .env file at the root of the project, and define the following:
  - AUTHORIZATION_END_POINT=
  - TOKEN_END_POINT=
  - CLIENT_ID=
  - CLIENT_SECRET=

2. `npm install`
3. `node client.js`
4. Access to http://localhost:9000/
5. You can click 'Get Oauth Token' to request for the access token.
