# Full-Stack-Bookstore-App
![full-stack-book-store-mern-project](/frontend/src/assets/github-cover.png)

## How to run this project:

### For Frontend 
Follow the below steps to run the project: 
- Firstly clone or unzip the project folder.
* Go to the frontend directory by using the following command ``` cd frontend ```.
* * create a **.env.local** file in the backend root directory as the same level where the **package.json** is located and keep the following environment variables there:
```
>>> Stepup firebase app and configure the environment

VITE_API_KEY=AIzaSyDaJColDSAhU-MphtEuk8oatXUOHFzOXnM
VITE_Auth_Domain=bookstore-a0518.firebaseapp.com
VITE_PROJECT_ID=bookstore-a0518
VITE_STORAGE_BUCKET=bookstore-a0518.firebasestorage.app
VITE_MESSAGING_SENDERID=887717430708
VITE_APPID=1:887717430708:web:ee427c84fbb284a9435ee1
```
+ Then run `` npm install `` commend to install node dependencies.
- Finally, to run the project, use ``npm run dev`` command.


### For Backend
Follow the below steps to run the project: 
- Firstly clone or unzip the project folder.
* Go to the backend directory by using the following command ``` cd backend```.
+ Then run `` npm install `` commend to install node dependencies.
* create a **.env** file in the backend root directory as the same level where the **package.json** is located and keep the following environment variables there: 
```
DB_URL = mongodb+srv://megha:megha_0204@cluster0.lqf7cit.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET_KEY = your_jwt_secret_key

Note: Please setup mongodb and change the MongoDB url and set your jwt secret key above.
```

- Finally, to run the project, use ``npm run start:dev`` command.
