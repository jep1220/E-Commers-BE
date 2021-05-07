# E-Commers-BE

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```


[Google Drive Video Link](https://drive.google.com/file/d/12xOAota1NX9Q39g1FLXKZ2HPvXmFzCwP/view)

![Untitled_ May 6, 2021 8_00 PM (1)](https://user-images.githubusercontent.com/38770396/117392794-a838d380-aea7-11eb-8fe8-5faf620ec6c3.gif)

![Untitled_ May 6, 2021 8_08 PM (1)](https://user-images.githubusercontent.com/38770396/117392746-95260380-aea7-11eb-970f-c9e86db8143b.gif)



## Installation
   
  
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## Usage
 
  
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter PW when promted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`
