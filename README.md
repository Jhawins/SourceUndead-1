SourceUndead
============

Multi-player [in progress] zombie game built with MySQL, Express, and NodeJS (The MEN stack).

I left out my settings.js file because it has private credentials in it. But here is the schema I used (a simple JS Object) to have my settings all in one file:

    var settings = {};
    
    settings.db = {};
    
    settings.db.user = "what is html"; //not real
    settings.db.database = "dat db"; //not my db
    settings.db.password = "asswordp"; //not my password either
    
    module.exports = settings;

Setting up your own server is easy! The following steps should help you create and setup your server.

1. Install an Ubtuntu 14.04 instance
2. Create your non-root user and give sudo permissions
3. Install a mysql server by running `sudo apt-get install mysql`
4. Install npm by running `sudo apt-get install npm`
5. Run `npm install` to install the project dependencies
6. Login to mysql using the credentials you created
7. Run `database.sql` to create the database and tables
8. Finally -- `node server.js` to start up the server!
