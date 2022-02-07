# E-commerce Back End Starter Code

# eSean An E-Commerce Backend
 
   
  
  ## Table of Contents
  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Walkthrough](#Walkthrough)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)
  * [Credits](#credits)
  
  ## Description
  AS A manager at an internet retail company
  I WANT a back end for my e-commerce website that uses the latest technologies
  SO THAT my company can compete with other e-commerce 
  
  Acceptance Criteria
  GIVEN a functional Express.js API
  WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
  THEN I am able to connect to a database using Sequelize
  WHEN I enter schema and seed commands
  THEN a development database is created and is seeded with test data
  WHEN I enter the command to invoke the application
  THEN my server is started and the Sequelize models are synced to the MySQL database
  WHEN I open API GET routes in Insomnia for categories, products, or tags
  THEN the data for each of these routes is displayed in a formatted JSON
  WHEN I test API POST, PUT, and DELETE routes in Insomnia
  THEN I am able to successfully create, update, and delete data in my database

  ## Installation
  Navigate to the github repository and clone it to you machine. Next you will need to create your own .env file. Create a .env file and enter your mysql login information. Now you can run npm install to install all the required packages.

  ## Usage
  To use, first login into the mysql shell and create the database using the command source db/schema.sql. Next, exit the shell and run the command source npm run seed. This will populate the database, allowing you to test it. Finally, run npm start to turn on the server. You are now ready to test all the routes with insomnia

  ## License
  This application was created as a part of the OSU Code Bootcamp - Web Development

  ## Walkthrough
  https://drive.google.com/file/d/1I0AoayYqG25upIJsHRjDQyp9YG_UPQpu/view

  ## Contributing
  No contributions at this time

  ## Tests
  No tests required

  ## Questions
  Have questions about this project?  
  GitHub: https://github.com/scollins117  
  Email: seancollins117@gmail.com

  ## Credits
  Sean Collins