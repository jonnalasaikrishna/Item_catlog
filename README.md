# Item_catlog
Fourth project

## Overview of Item Catalog Project:

       The Item Catalog project consists of developing an application that provides a list of items 
    within a variety of categories,as well as provide a user registration and authentication system. 
    Authenticated users will have the ability to post, edit,and delete their own items. 


## PreRequisities:

  1) `HTML` 
  
  2) `CSS`
  
  3) `Vagrant`
  
  4) `VirtualBox`
  
  5) `Google`
  
  6) `Flask`
  
  7) `SQLAlchemy`

## steps to run this project:

1. Install `Vagrant` and `Virtual Box` on your machine.

2. Launch the Vagrant VM by using Following commands

    `vagrant up`
    
    `vagrant ssh`
    
3. To Initialize Database and To initialize the SQLite database

   `$ python database_setup.py`

4.  load the employee data

    `$ python emplist.py`

5. To start the application or to run the project on the server
    `$ python finalemp.py`

6. The web app will be running on your localhost at port 7000 ( http://localhost:7000/ )

7. Open the above mentioned link to use the web app.

8. You can only view the catalog without signing in.

9. To create, update and delete the items in the catlog, sign in using Google+.

10. To login using Google+ `http://localhost:7000/login` to login to the app
   To Use Google Authentication Services

     `We will need a client_secret.json file`.

13. We can create an application to use Google's OAuth service at https://console.developers.google.com.
    After creating and downloading client_secret.json file, move it to the directory where it is accessible 
    to the project file. This project uses persistent data storage to create a web application that allows
    users to perform Create, Read, Update, and Delete operations.   


