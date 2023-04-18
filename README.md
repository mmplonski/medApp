# REST API of the medical center
## Brief description of the project
The project is an application written in Java 17 using Spring Boot.
It is written in a microservices architecture. It consists of 5 microservices. It uses SQL H2 database and noSQL MongoDB.
## How to run a project on Linux/MacOS
Make sure you have Java 17 installed. Type "java -version" in the terminal. If the Java version starts with "17" e.g. "17.0.2" then everything is ok.
Then navigate through the terminal to the med-app folder. Then enter the command "sh kill.sh" this will kill the processes on the ports used by the application (8080, 8087, 8088, 8761, 9000). Then type "sh start.sh". This will start all microservices.
You can check if everything is up and running by typing "http://localhost:8761/" in your browser. You should see the Eureka console with 4 apps registered in it. Just like in the picture below.
![](./images/eureka.png)
