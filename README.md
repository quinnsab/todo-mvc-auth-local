# Manage Your Project

Track your tasks in your Professional Work, Personal Work, Chores, Events, and Recreation. 

A ToDo App built using the MVC Architecture, we have also implemented "authorization" so users can sign up, customize & return to the app with those changes still applied. 

---

# How It's Made

**Tech Used:** HTML, CSS, JavaScript, EJS, Express, MongoDB

- Using MVC architecture and "authorization", it's a todo app that allows users to sign-up, customize and return to the app when needed.
- Manage Your Project is split up into two separate deployables, a web client and a backend server.

---

# Who is this for? 

- It's for anyone who wants to see the effects of implementing authorization and MVC in an app. 

---

# Packages/Dependencies used 

bcrypt, connect-mongo, dotenv, ejs, express, express-flash, express-session, mongodb, mongoose, morgan, nodemon, passport, passport-local, validator

---

# How to run the App 

- After cloning the repo, install all the dependencies or node packages used for development via Terminal using the command `npm install`.
- Create a separate .env file to connect and add the following as `key: value`.
  - PORT: 2121 (or any other port example: 3000)
  - DB_STRING: `your database URI`
    - Note: If Port doesn't work, change the port number to 5000.
- Make sure the .gitignore file lists .env 
- Then `npm start` and connect to your localhost to see the rendered server. 

---

# How it works

Users can sign-up with a new account or sign-in to return to the app at a later time. Once logged in, users can also log out. 

When using the app for the first time, users can enter a todo task that they want to store in the app. 
Then they can select the category it should be stored under by clicking on one of the radio buttons and hitting submit.
Upon submitting, that task will show up on the screen as a list item under the Todos heading.
They can continue to add more tasks to any available categories. 
Once submitted, the user can see their tasks all listed out. These tasks can then be deleted by the user when needed.
The app also includes a feature that allows the user to filter submitted tasks by categories. 
So for example, if they submitted 5 tasks with the professional work category and 5 tasks under the chores category, using the drop-down filter 
to filter for professional work will display only those tasks associated with professional work. 

The users will also see how many total tasks they have left on their todos with the app.
This will be specified and updated with the message: <%= user.userName %> has <%= left %> things left to do. 

---

# Optimizations

Here are some additions to the app we would have made given a longer timeframe: 
- Add level of importance to each todo
- Create buttons to sort by categories
- Create a design for the main todo page

---

# Lessons Learned: 



