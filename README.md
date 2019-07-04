# pane-backend
[Prisma](https://www.prisma.io/), [Apollo](https://www.apollographql.com/), [Node](https://nodejs.org/en/), [Express](https://expressjs.com/) backend stack implementation in JavaScript with [Flow](https://flow.org/) as a static type checker

Currently supports user signup and login along with file uploads

## Getting started
1. [Setup Prisma on your server](https://www.prisma.io/docs/1.34/get-started/01-setting-up-prisma-new-database-JAVASCRIPT-a002/)

2. Check if Prisma is running by opening Prisma Admin at http://localhost:4466/_admin if Prisma (usually runs in a Java process that starts by default on boot) is not running, start it by running this in terminal:  
  ```yarn run run-prisma```  
  or  
  ```npm run-script run-prisma```
  
3. Make sure you have all of the node modules installed by running this in terminal:  
  ```yarn```  
  or  
  ```npm install```
  
4. Run the server:  
  ```yarn run watch```  
  or  
  ```npm run-script watch```
  
5. Or build it for deployment later:  
  ```yarn run build```  
  or  
  ```npm run-script build```
  
6. When you make any changes to Prisma data model you need to run this:  
  ```yarn run update-prisma-datamodel```  
  or  
  ```npm run-script update-prisma-datamodel```
