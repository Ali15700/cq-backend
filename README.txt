Npm init
to creare package.json file
npm i express pg cors
express is a way to create server nodejs
pg cors is a way to integrate and interact with postgres database

I have used Postgresql for storing data locally and for relational database management system

Create database.sql file where I create Database and tables of student and book


Open command prompt then …
psql -U postgres
 (Postgres is a superadmin having access on inside database)

\l  (you can see all your data)
\c (you can move in database  e.g \c postgres)
Database.sql (you also have to add the commands in psql prompt)
\dt (to check the relationships)

Db.js (Pg give us Pool query to connect the database with the server) and add information related to where you store data and connect with your Database.

In Index.js I perform CRUD operation for each table. 


