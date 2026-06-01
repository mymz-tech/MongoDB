# MongoDB

## Task 1

1. What is MongoDB?
```
MongoDB is a document database built on a horizontal scale-out architecture that uses a flexible schema for storing data.
Instead of storing data in tables of rows or columns like SQL databases,
each record in a MongoDB database is a document described in BSON, a binary representation of the data.
Applications can then retrieve this information in a JSON format.
```   
2. Advantages and DisAdvantages of MongoDB?
```
Its an Open source Database.
MongoDB can handle high volume and can scale both vertically or horizontally to accommodate large data loads.
Works with most of the programing languages.
Easy Maintanence
Real time data handling
```
3. Common use cases for MongoDB?
```
IOT Devices
Gaming and Mobile Application
CMS and CRM systems
Web Applications
Where Schema changes rapidly
E-commerce aplatforms
Log management and monitoring
```
4. Connecting to MongoDB locally, using Compass
```
Click Connect to localhost:27017
Click open mongo db shell
```
5. Creating a new database
```
click + icon near localhost
click create new database
Enter database name
Enter collection name
```
6. Creating a new collection
```
on Shell
Switch to the database using command > use sparta
Create collection using command > db.createCollection("institute")
```
7. Adding a document and adding multiple documents
```
Adding single document
db.institute.insertOne({name:"New document"})
```

```
adding multiple document by this command
db.institute.insertMany([{"course":"Data Engineering"}, {"course":"Data Analysis"}])
```

## To be continued
## Task 2

1. Validation
Create a new collection called "students"
Find out how to implement Validation on the documents we want to create.
This can be done either with the Compass GUI or Mongosh. Show how to do it for at least 1 of those options.
```
create collection
go to the vaidation tab

Showcase an invalid entry after setting up Validation and then a valid entry.
What output do you get each time?
```
set up the rules

age must be integer
email must contain @
```
```





