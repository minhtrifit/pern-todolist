> # PERN TO DO LIST TUTORIAL

### Make sure you have installed:
[Postgresql](https://www.postgresql.org)<br>
[Node](https://nodejs.org/en/)

## Step 1: Install all packages for app
At Server folder, using command (Do the same thing at Client folder):
~~~
npm install
~~~

## Step 2: Import database script to your local postgresql
Use file: (Make sure you have created new database before)
~~~
Server/db.sql
~~~

## Step 3: Setting your local postgresql
Go to: 
~~~
Server/config/dbConfig.js
~~~

## Step 4: Run Server first (port: 5000), after that run Client (port: 3000)
+ At Server folder:
~~~
npm run dev
~~~
+ At Client folder (Make sure you run Server successfully):
~~~
npm start
~~~

## Step 5: Enjoy !


***Copyright ©: github.com/minhtrifit - Do not reup***
