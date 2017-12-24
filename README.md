This project is to help as a bare bones boiler plate for MERN stack apps.
Uses redux with react for authenticating and signing up users.



Instructions:
  - Clone or download. 
 ```
  cd boiler-client
  npm install --save
  cd ../boiler-server
  npm install --save
 ```
 Create .env file. In the file add:
 ```
  SECRET_KEY=longRandomStringOfCharacters
 ```
 Do not check in this file
 - From boiler-server run :
  ```
   npm start
  ```

## Fontend Technologies:
- react using create-react-app
- redux
- react-router
- redux-thunk

## Backend Technologies:
- mongo & mongoose
- node & express
- bcryptjs
- jsonwebtoken
