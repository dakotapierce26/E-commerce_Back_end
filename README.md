# E-Commerce Backend
This project was built for module 13 to demonstrate Object-Relational Mapping, or ORM. This project utilizes Express, Sequelize, and MySQL to store, update, remove, and add items in a shopping catalouge for an E-Commerce web page.

## Installation and operating guide

### Installation Guide
Upon forking this repostiory and putting it on your local machine, in your command line run the following code:
```npm init```

```npm install sequelize```

```npm install mysql2```

```npm install dotenv```

### Operating Guide
After successfully installing your npm's you will need to log in to MySQL to start the app.

```mysql -u root -p```

Enter your password when promted

```source db/schema.sql```

```quit```

```npm run seed```

```npm start```

You should now be able to use Insomnia to try out the database by using Get, Put, Post, and Delete requests

## Walkthrough Video
![Walkthrough showcase](Develop/assets/Walkthrough.gif "Walkthough video")

## Contributors
Ashton Pierce

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[ISC](https://choosealicense.com/licenses/isc/)
