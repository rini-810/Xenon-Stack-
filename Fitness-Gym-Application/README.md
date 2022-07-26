**Fitness-Gym_Application** : 
It is a Fitness Gym Application hosted on Heroku. It uses NodeJs as backend, and frontend is based on HTML, CSS and JavaScript. It hosts the Mongo database on Mongo Atlas. User can create an account and purchase different packs based on his/her needs. This pack will be added to his/her purchase history.

**BackEnd** : 
Based on Nodejs. uses Express for web pages rendering. User data is saved on Mongo Atlas cloud and passwords are saved after they are hashed using bcryptjs. 
Used JsonWebToken for authentication of user. When user sign in / creates an account a cookie is generated and saved, this cookie will be used out through the session to authorize the user.
When  user wants to login the id is then matchhed with token to authorize the user.

**FrontEnd** :
Frontend consist of HTML. The view engine used is Pug. We use view engine to access variables in HTML pages. Have not used any external css. And used JavaScript to implement the Hamburger menu and cross mark for flash notifications.

**Database** :
MongoDb database is used. Since it is flexible and not sql its the best choice to use in this scenario. Stores username, password (hashed), purchase history, tokens, email and other stuff.
Hosted on Mongo Atlas.

**Deploy** :
Deployed on heroku. A free web hosting platform. 


**Running the Application** :
Step 1 - Clone the repo on your local device

Step 2 - run commmand "npm install"
To install all the dependencies in the package.json. A new folder named node_modules will be created which will consist of all modules.

Step 2 - npm run dev
Starts the application using dev script in package.json.
npm run dev will fire the command nodemon src/inedx.js -e js,ejs,pug 


**Visit the application here** :
https://magic-fitness-gym.herokuapp.com/

<h1>ScreenShots<\h1>





![Screenshot (2)](https://user-images.githubusercontent.com/108979543/181069804-5479aebf-6dd1-4dd4-b75b-d6c5649bff61.png)
![Screenshot (3)](https://user-images.githubusercontent.com/108979543/181069817-47141e81-c97b-4776-8349-ab383f37fcac.png)
![Screenshot (4)](https://user-images.githubusercontent.com/108979543/181069826-20e2cf07-f6c2-4e03-83fa-9ce6f54e0434.png)
![Screenshot (1)](https://user-images.githubusercontent.com/108979543/181069832-0ec970e4-1874-4c35-af7a-56bbd2bd01c1.png)













