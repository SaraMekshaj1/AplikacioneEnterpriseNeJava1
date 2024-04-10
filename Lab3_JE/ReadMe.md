Along this project we are using Spring Boot, Spring Data JPA AND MYSQL database .

Step 1: Setting Up my Spring Boot Project
I created a Spring Boot application in Spring initalizr , Project :Maven
Spring boot 3.2.4 
Packaging type: Jar
Java 17
 I have added  these depencies: 
MySQL Driver 
Spring Web 
Spring Data JPA 

Step 2: Setting Up the Database
Create a MySQL database
I modified properities of project adding my  database configuration.

Step 3: Project Dependencies = Tree Format
'mvn dependency:tree'  command to  generate a tree-like representation of my project's dependency tree. This command is useful for visualizing the dependencies of your project, including transitive dependencies (dependencies of dependencies).

Step 4: Entity
I have created a Java Class named Book in my package

Step 5: Creating the Repository
Create a new Java interface named BookRepository

Step 6:  Creating the Controller
Create a new Java class named BookController

Step 7: Creating The Service :
Create a new Java class named BookService

Step 8: Run the application

Step 9 : Testing the Application
I used  Postman to interact with the endpoints



![alt text](image.png)
![alt text](image-1.png)
In mysql is added book information: 
![alt text](image-2.png)


