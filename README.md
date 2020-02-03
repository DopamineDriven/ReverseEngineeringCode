# ReverseEngineeringCode
Dissecting the app file by file via google docs; Passport, Node, Sequelize


# Google Doc
https://docs.google.com/document/d/1rRF8fR1gxQpL1yGfBqbZZhWqRV4NfQg4U2PJPnAkikw/edit?usp=sharing


# Directory Structure

│ 
├── config
│   ├── middleware
│   │   └── isAuthenticated.js
│   ├── config.json
│   └── passport.js 
│         
├── models
│   ├── index.js
│   └── user.js
│ 
├── node_modules
│
├── public
│   ├── js
│   │   ├── login.js
│   │   ├── members.js
│   │   └── signup.js
│   ├── stylesheets
│   │   └── style.css
│   ├── login.html
│   ├── members.html
│   └── signup.html
│         
├── routes
│   ├── api-routes.js
│   └── html-routes.js
│ 
├── .gitignore
│ 
├── package-lock.json
│ 
├── package.json
│
├── README.md
│
└── server.js

## npm dependencies

- mysql2 -- https://www.npmjs.com/package/mysql2
- express -- https://www.npmjs.com/package/express
- express-session -- https://www.npmjs.com/package/express-session
- body-parser -- https://www.npmjs.com/package/body-parser
- nodemon -- https://www.npmjs.com/package/nodemon
- sequelize -- https://www.npmjs.com/package/sequelize
- passport -- https://www/npmjs.com/package/passport
- passport-local -- https://www/npmjs.com/package/passport-local
- bcryptjs -- https://www.npmjs.com/package/bcryptjs

Unit 14 Sequelize Homework: Reverse Engineering Code
Reverse engineer the starter code provided and create a tutorial for the code.
In the Develop folder, there is starter code for a project. Begin inspecting the code to get an understanding of each file's responsibility. Then, in a Google Doc, write a tutorial explaining every file and its purpose. If one file is dependant on other files, be sure to let the user know.
At the end of the tutorial, add instructions for how you could now add changes to this project.
Following the common templates for user stories, we can frame this challenge as follows:
AS A developer

I WANT a walk-through of the codebase

SO THAT I can use it as a starting point for a new project

Business Context
When joining a new team, you will be expected to inspect a lot of code that you have never seen before. Rather than having a team member explain every line for you, you will dissect the code by yourself, saving any questions for a member of your team.

Acceptance Criteria
GIVEN a Node.js application using Sequelize and Passport
WHEN I follow the walkthrough
THEN I understand the codebase


Submission on BCS
You are required to submit the following:

A link to a Google Doc or video explaining the application in Develop/.

Note: Don't forget to change the sharing settings on your Google Doc.