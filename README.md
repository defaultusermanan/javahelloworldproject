# Java Hello World Project

This repository contains a basic Java Hello World application built using Maven. The project demonstrates how to set up a CI/CD pipeline and perform code quality analysis.

## File Structure

```
.github/workflows/cicd-pipeline.yml - Defines the CI/CD pipeline.
.github/workflows/codeql.yml - Defines the CodeQL analysis workflow.
java-hello-world-with-maven-master/ - Contains the Java Hello World source code.
```

## Prerequisites

- Java 11+
- Maven
- GitHub Actions enabled

## Running Locally

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd java-hello-world-with-maven-master`
3. Build the project: `mvn clean install`
4. Run the application:
   ```bash
   java -cp target/hello-world-1.0-SNAPSHOT.jar hello.HelloWorld
   ```

## Continuous Integration

The project uses GitHub Actions for CI/CD and CodeQL analysis. See the `.github/workflows` directory for workflow definitions.