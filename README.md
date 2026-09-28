# Java Maven Project

A simple Java project built with Maven as part of Semester 7 of our engineering programme at **IMT Atlantique**.

Course reference: [Stéphane Bouchet - emn-fil](https://github.com/sbouchet/emn-fil/tree/master).

## Build and run

Requires a JDK (Java 8 or newer) and Maven. From the project directory:

```bash
mvn clean package
java -jar target/maven-archetype-simple-1.0-SNAPSHOT.jar
```

The build compiles the code, runs the tests, and creates the JAR in `target/`. The application prints `Hello World!`.
