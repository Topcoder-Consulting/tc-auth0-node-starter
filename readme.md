# auth0-node-starter

A barebones starter application for Auth0 and the topcoder API. Provides login functionality, security and viewing user info.

## Auth0 Settings

Talk to the platform team about getting your callback URL setup.

## Local Installation Instructions

From the command line type in:

```
git clone git@github.com:topcoderinc/tc-auth0-node-starter.git
cd tc-auth0-node-starter
npm install
```

### Running the Application Locally

1. Open terminal and change directory to tc-auth0-node-starter root
2. Export the following variables to your environment from Auth0.

```
export AUTH0_DOMAIN=YOUR-AUTH0-NAMESPACE
export AUTH0_CLIENT_ID=YOUR-AUTH0-CLIENT-ID
export AUTH0_CLIENT_SECRET=YOUR-AUTH0-CLIENT-SECRET
export AUTH0_CALLBACK_URL=http://localhost:8000/callback
export AUTH0_SCOPE='openid'
```

3. Start the server with `node app.js`
4. Point your browser to: [http://localhost:8000](http://localhost:8000)

## Contributors
* Jeff Douglas -> [jeffdonthemic](https://github.com/jeffdonthemic)
