# Java Hello World with Maven

This project contains a simple Java Hello World example configured to use Maven.

## Building the Project

Run the following command to build the project:
```bash
mvn clean install
```

## Running the Project

Navigate to the target folder and execute the compiled JAR:
```bash
java -cp target/hello-world-1.0-SNAPSHOT.jar hello.HelloWorld
```

## Source Code

### Greeter.java
A utility class to generate greeting messages.

### HelloWorld.java
Main application entry point.