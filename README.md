
  # Title
  ## Tech-Blog
  
  [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
  ## Table of contents 
  - [Description](#description)
  - [Installation](#installation)
  - [Usage Information](#usage-information)
  - [License](#license)
  - [Screenshot](#screenshot)
  - [deployed](#deployed)
 
  
  ## Description
     This application built on nodejs, express, handlebars and sequelize. This application structure follows the Model-View-Controller pattern, and mysql2, dotenv, bcrypt library are used. Overall, this CMS style blog application gives 
     user to create account, update, delete the content, also allows to see the blog with sign on webapp.     

  ## Installation
     first need to clone from given github link and need to perform 'npm i' on terminal within the project location. 
     Second, type on terminal 'npm run seed' to get test for application if not then you can put your own data or 
     use application to create data.
     Third, 'node server.js' or 'npm start' to run the actual application. 
     Finally, the application will run and allows blogging.

  ## Usage Information
     It is useful to create blog on topic, and provides the platform for comment on blog. User can able to delete and edit 
     only their own blog but not others blog. User can comment on any blog after sign in to web application

  ## License
     MIT license
  
 
  
  ## Screenshot
  ### welcome Screen
  ![welocome](./public/images/welcome.PNG)

  ### sign up 
  ![signup](./public/images/signup.PNG)
  
  ### dashboard 
  ![dashboard](./public/images/dashboard.PNG)
  
  ### comment page
  ![commment](./public/images/comment.PNG)

  ### edit page
  ![edit](./public/images/edit.PNG)  

  ## deployed
  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://andreas-tech-blog.herokuapp.com/)
