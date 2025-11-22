# gson-stream-iterator

A Java Maven project with groupId: `gson-utils` and artifactId: `gson-stream-iterator`.

## Prerequisites

- Java 17 or later
- Apache Maven 3.6 or later

## Building the Project

To compile the project:

```bash
mvn clean compile
```

To run tests:

```bash
mvn test
```

To package the project:

```bash
mvn clean package
```

## Running the Application

After building, you can run the application with:

```bash
java -cp target/gson-stream-iterator-1.0-SNAPSHOT.jar gsonutils.App
```

## Project Structure

```
gson-stream-iterator/
├── pom.xml
├── README.md
└── src/
    ├── main/
    │   └── java/
    │       └── gsonutils/
    │           └── App.java
    └── test/
        └── java/
            └── gsonutils/
                └── AppTest.java
```

## Configuration

- **Java Version**: 17
- **JUnit Version**: 5.10.1
- **Maven Compiler Plugin**: 3.8.0
