# Twilio Flex UI Sample

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

You can find the most recent version of the guide on how to perform common tasks [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

This package can only be consumed together with Twilio Flex. Visit http://twilio.com/flex to find out more.

## Instructions

1. Install all dependencies by running:
```
npm install
```
2. Copy appConfig.sample.js in public/assets folder 
```
cp public/assets/appConfig.sample.js public/assets/appConfig.js

```
3. Read the comments section and update the following:
    1. accountSid to be updated with your Twilio Flex Project ID
    2. Uncomment the appConfig Block

4. Login to your Twilio account which will keep the session alive for SSO to go through

5. Start Flex UI by running:
```
npm start
```