# @euriklis/database library
This is a free, non relative database in javascript based on the combination of the functionalities of the @euriklis/sortlib and the @euriklis/validator libraries. The first one is oriented to the sorting of the data and the second one is specialized on the scheme or the architecture of each database. We will use the express.js package to manage the database with requests. The main idea is providing a REST-full API that allows to the use to manage the process of database cycle, i.e., the creating of a database, definding of schemes of this database, adding elements to the database, deleting and the updating of elements or parts of elements of the database, the finding and searching into the databases and other.
# Main idea and structure:

The database is a complex construction which consists of three components, namely, the Database instance, which includes all the methods of the Database class, the API of the library which includes all the requests for managing of the database and the physical instance of the Database, i.e., the file which saves/records the entries wchich are made from the user. 

So it is usefull to use the so called MVC pattern in the development process of the database. In the View module we implement the API fragment of the package with the using of express.js package. In the Models module we will embody the Database class instance and the database files which stores the data and the programm controll flow will be navigated from the Controllers module. 

 
