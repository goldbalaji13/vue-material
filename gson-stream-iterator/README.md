# gson-stream-iterator

A utility JAR library for Gson stream iteration with groupId: `gson-utils` and artifactId: `gson-stream-iterator`.

## Prerequisites

- Java 17 or later
- Apache Maven 3.6 or later

## Dependencies

- **Gson**: 2.11.0
- **Jackson**: 2.18.2 (core, databind, annotations)
- **JUnit Jupiter**: 5.10.1 (test)

## Building the Project

To compile the project:

```bash
mvn clean compile
```

To run tests:

```bash
mvn test
```

To package the utility JAR:

```bash
mvn clean package
```

## Usage

Add this utility JAR as a dependency in your project:

```xml
<dependency>
    <groupId>gson-utils</groupId>
    <artifactId>gson-stream-iterator</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
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
    └── test/
        └── java/
            └── gsonutils/
```

## Configuration

- **Java Version**: 17
- **Gson Version**: 2.11.0
- **Jackson Version**: 2.18.2
- **JUnit Version**: 5.10.1
