## About
This application is a social platform for sharing posts. 

Users can sign up, log in, add a profile photo, create a written post, upload a photo, comment and like other posts and like comments

## Technologies

Here's an overview of the technologies used to build this application. 

- MongoDB
- Express
- React
- Node.js
- Bootstrap
- Jest
- Cypress

## Quickstart

### Set up your project

1. Clone this repo 
```
git clone https://github.com/sarahdavies186/acebook-water.git
```

2. Install NPM dependencies
```
; cd api
; npm install
; cd ../frontend
; npm install
```
3. Install MongoDB
```
brew tap mongodb/brew
brew install mongodb-community@5.0
```
4. Start MongoDB
```
brew services start mongodb-community@5.0
```
### Start

1. Start the server
```
; cd api
; JWT_SECRET=SUPER_SECRET npm start
```
2. Start the front end

  In a new terminal session...
  
 ```
 ; cd frontend
 ; npm start
 ```

Browse to [http://localhost:3000/signup](http://localhost:3000/signup) to create a new user.

Then, after signing up, you should be able to log in by going to [http://localhost:3000/login](http://localhost:3000/login).

### Testing

#### The Backend (API)

**Note the use of an environment variable for the JWT secret**

  Start the server in test mode (so that it connects to the test DB)

  ```
  ; cd api
  ; JWT_SECRET=SUPER_SECRET npm run start:test
  ```

  Then run the tests in a new terminal session

  ```
  ; cd api
  ; JWT_SECRET=SUPER_SECRET npm run test
  ```

#### The frontend (React)

**Note the use of an environment variable for the JWT secret**

  Start the server in test mode (so that it connects to the test DB)

  ```
  ; cd api
  ; JWT_SECRET=SUPER_SECRET npm run start:test
  ```

  Then start the front end in a new terminal session

  ```
  ; cd frontend
  ; JWT_SECRET=SUPER_SECRET npm start
  ```

  Then run the tests in a new terminal session

  ```
  ; cd frontend
  ; JWT_SECRET=SUPER_SECRET npm run test
  ```
## Demo

<img width="1413" alt="Screenshot 2023-06-01 at 13 52 52" src="https://github.com/sarahdavies186/acebook-water/assets/99144401/604db8e3-a783-4ad6-90ce-91a55180df94"> <br/>
<br/><img width="1420" alt="Screenshot 2023-06-01 at 13 56 03" src="https://github.com/sarahdavies186/acebook-water/assets/99144401/44a3b393-091e-4a7b-814c-cc65455f225e"> <br/>
<br/><img width="1397" alt="Screenshot 2023-06-01 at 13 56 34" src="https://github.com/sarahdavies186/acebook-water/assets/99144401/5a6f1174-fa4d-4805-9aa5-933c0dbcf252">

## Contributors 

This was a group project, created by: 
- Sarah Davies 
- Dilan Patel
- Ayoub El-Hamdoon
- Keremet Sultanalieva
- Sonjay Kumar


---






