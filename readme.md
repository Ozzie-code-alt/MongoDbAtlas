MongoDB No-SQL 
Uses json-like  instead of rows and tables 

Document = group of field value pairs to represent an Object

Collection = is a Group of 1 or more documents

Database = collection of Groups 

Pre req - OOP

# MongoDB syntax 
- show dbs = will show us a list of databasese
- use <db_name> = switch to a database / also create a blank db
- db.createCollection("students") = this is to create a collection/table in a database

- db.dropDatabase()


# Inserting in Databases 

Note: if db is not present but u typed db.students in cmd it will make the db 


- db.students.insertOne({name:"Justin", age:30, gpa:3.2}) = insert key/value pairs in our collection

- db.students.find() = return a collection of students

-db.students.insertMany([{name:"Sheina", age:40, gpa:1.5},{name:"LeoVino, age:60, gpa:4.0"},{ name:"Vee", age:10,gpa: 2.5}])

# DataTypes in Mongo DB