2. Data processor 

This application will help to parse the complex JSON format into readable and storable data into the database. The input for the application will be a complex JSON like below and the objective is to parse this JSON effectively and help in effective querying of data from the database. 

college : { 

name : "London College" 

address : "Birmingham" 

departments : [ 

{ 

"name" : "CSE" 

"HOD" : "John" 

classes : [ 

{ 

name : "Batch-1" 

staffName : "Jacob" 

capacity : 40 

students  : [ 

{ 

name : "Ganesh" 

dateOfBirth: "10-Apr-1990" 

} 

] 

} 

] 

} 

] 

} 

We will need to design and develop the API’s created using the above-listed technologies and call these API’s using Postman. 

Read and parse the sample data as shared above for storing into database. 

Once the data is parsed, retrieved and effectively stored into the database, we should be able to perform the below actions. 

List all the colleges 

List all the departments 

List all the classes under each department 

List all the students in each class 

Able to search and find for a specific student and display the details. 