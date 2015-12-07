# Phonebook
The same app is placed on http://provisdemo.com/phonebook/ , please always try it out there with same given credentials below to understand the basic functionalities offers by the application. 

#Installation and Running
 
1.Please download the code and find the phonebook_db.sql , create a mysql database and import the given sql. 

2. Place the phonebook directory on your Web Server root directory and update the database details in following file as follows 

   /your-server-root/phonebook/.env

   you need to update following code 
   
  DB_HOST=localhost
  DB_DATABASE=“your database name”
  DB_USERNAME=“your database user”
  DB_PASSWORD=“your database password”


3. please update permission /your-server-root/phonebook/storage directory requires at least 0755. ( please check / change ownership of the phonebook directory to the user running Web Server. otherwise 0777 permission is required for storage directory )  

5. All set , you can check the application on following URL 

http://your-server-hostname/phonebook/public
