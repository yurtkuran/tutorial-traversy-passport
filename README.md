# tutorial-traversy-passport
Brad Traversy's YouTube tutorial using NodeJS and Passport

https://www.youtube.com/watch?v=6FOq4cUdH8k

Original githup repo: 
https://github.com/bradtraversy/node_passport_login

The original tutorial used MongoDB and EJS. I modified the app to use MySQL and Handlebars instead. Also incorperated:
+ sequelize
+ bootstrap navbar with conditional menu items based on user login and admin status
+ email confirmation wiht nodemailer and  JWT
+ dotenv to store configuration infomration (ie passwords, keys, etc)
+ dtabase log when user logs in or out
+ user CRUD
+ multiple access levels: member & admin
+ momentjs for time formatting 
+ bootstrap modal pop-up delete confirmation
+ field validation using express-validator
