# Easy Node Authentication with Okta

Based on the Scotch.io example here:  http://scotch.io/tutorials/easy-node-authentication-linking-all-accounts-together

Uses techstars passport-okta-oauthto authentication to a free developer tenant in Okta - http://www.passportjs.org/packages/passport-okta-oauth/

Get an Okta Developer tenant here:  https://developer.okta.com 

## Instructions

If you would like to download the code and try it for yourself:

1. Clone this repo
2. Install packages: `npm install`
3. Configure it to use your Okta tenant via OpenIDConnect
4. Whitelist the following urls in the App 

Login URIs:
http://localhost:8080/auth/okta/callback

http://localhost:8080/auth/okta

Logout URIs:
http://localhost:8080

http://localhost:8080/auth/okta/callback

http://localhost:8080/auth/okta

Initiate Login URI:
http://localhost:8080/auth/okta/callback

5.  Whitlist the following urls in CORS:
http://localhost:8080

5. Launch the app: `npm start`
6. Visit in your browser at: `http://localhost:8080`

Note:  Runs on SVR4 linux only (MacOS or Linux), if you are Windows and need a development environment to try this out use the CFT located here:  https://jgalvinoktacftdemotemplates.s3.us-east-1.amazonaws.com/Single%20Amazon%20AWS%20Instance%20us-east1%20with%20ASA%20enrollment.json.txt


## Many Thanks to TechStars and Scotch.io!  
