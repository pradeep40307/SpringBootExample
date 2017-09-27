# SpringBootExample

1. mvn clean
2. mvn test
3. mvn clean install 
4. Go to the target folder
5. java -jar demo-0.0.1-SNAPSHOT.jar
6. Verify your RESTful calls.

Get All ToDo’s
----------------
GET Request → http://localhost:8080/todo/

Get ToDo by Id
---------------
GET Request → http://localhost:8080/todo/4

Invalid Requests
------------------
GET Request for invalid id → http://localhost:8080/todo/0
