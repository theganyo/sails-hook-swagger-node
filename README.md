# Sails.js Hook for Swagger-Node projects

## Installing

### Swagger-Node greenfield app

This hook will automatically be installed and used when creating a Sails application through the 
[Swagger-Node](https://www.npmjs.com/package/swagger-node) cli. 

### Existing Sails apps

To add to an existing Sails app:

1. Install module as a dependency in your app: `npm install --save sails-hook-swagger-node`
2. Create a directory called api/mocks in your app
3. Create a directory called api/swagger in your app
3. Copy your `swagger.yaml` file to the api/swagger directory
4. Start your app: `swagger project start`  

