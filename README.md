# aller de Arquitecturas de Servidores de Aplicaciones, Meta protocolos de objetos, Patrón IoC, Reflexión

## Description
Java project in which its implemented a server with HTTP.

## Requirements

* Java 8 or higher
* Maven

## Project Structure

* **src/main/java/com/mycompany/springeci/HttpServer.java:** HTTP server.
* **src/main/java/com/mycompany/reflexion:** All the topic about reflections.
* **src/main/java/com/mycompany/springeci/HelloService.java:** REST controller.
* **src/main/resources:** Directory for static files.

## Installation

1. Clone the repository with:
```
   git clone https://github.com/RichiVilla/AREP-LAB03
 ```

2. Compile using maven

```
  mvn clean install
```

3. Run the project
   * For the reflection topic worked on class
      ```
        java -cp target/springeci-1.0-SNAPSHOT.jar com.mycompany.reflexion.JUnitECI com.mycompany.reflexion.ClassToBeTested
      ```
   * For the http server
       ```
            java -cp target/classes com.mycompany.springeci.HttpServer
       ```
     * Endpoints
          * GET /hello: Returns a greeting message.
          * GET /tomorrow: Returns the day of the week for tomorrow.
          * GET /goldenratio: Returns the golden ratio number.
          * GET /euler: Returns the value of Euler's number.
          * GET /currenttime: Returns the exact date and time.
          * GET /square?number=<number>: Returns the square of a number.
          * GET /sum?a=<number>&b=<number>: Returns the sum of two numbers.
          * GET /editor: Returns the editor's name.
          * GET /greeting?name=<name>: Returns a personalized greeting.
          * GET /city: Returns the city of Bogotá.
          
  * Running default service
    ```
     java -cp target/springeci-1.0-SNAPSHOT.jar com.mycompany.springeci.Springeci com.mycompany.springeci.HelloService
    ```

-----------------------------------

# REVIEW

 1. Running the server.
  ![image](https://github.com/user-attachments/assets/f15690e1-bd43-46b6-9db1-e1abc6f3ad8b)


 2. Using the server for multiple services that can offer.
  
![image](https://github.com/user-attachments/assets/64e4ae18-a1f9-466f-93a6-67dc2d565e1b)

![image](https://github.com/user-attachments/assets/bb44dc38-d7f4-4cba-a763-f3cedae19386)



3. With the cmd we can see that the server is running correctly and catching the parameters and requested paths.
   * Running the default service

        ![image](https://github.com/user-attachments/assets/74d1ca25-d839-4981-b2c9-45a138c2350d)

------------------------
# AUTHOR
Ricardo Villamizar
 


     
