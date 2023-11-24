### Prerequisites

Node.js installed

### Installing


* ===== Issue 1  ===== *

In server folder you need to create a folder name public and in public folder create another folder name uploads. In uploads folder you need create 3 folder like bellow.
Folder structure will be like: 
public -> uploads -> 1. products 2. customize 3. categories

Folder tree look like in server folder:
/public/uploads/categories
public/uploads/customize
public/uploads/products

* ===== Issue 2  ===== *

For admin signup just go to the auth 
controller then newUser obj, you will 
find a role field. role:1 for admin signup & 
role: 0 or by default it for customer signup.
Go user model and then you will see the field.

* ====== Issue 3  ===== *
         - For Run the project
	 * server: nodemon app
	 * client: npm start

Extremely sorry about all of the issue's!

Installing NPM modules on both frontend and backend folders

Execute these commands from the project directory

```
cd frontend && npm install || npm install react-chatbot-kit
```

```
cd backend && npm install
```

### Running the app

Open a terminal on backend directory

```
npm run start:dev
```

and open another terminal on frontend directory
```
npm run start
```

Access the web app at http://localhost:3000/

Admin:
Email: admin@gmail.com
Pass: admin@gmail.com

User:
Email: user1@gmail.com
Pass: user1@gmail.com

Paypal: sb-6uesj25098388@personal.example.com
pass: user1000
