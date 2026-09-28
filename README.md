# CI Setup Practice : Java and Maven

This repository is a continuous integration (CI) setup exercise for Semester 7 at **IMT Atlantique**. A small Java application provides a way to practise automated builds, test validation, and protecting `main` through pull requests.

Course reference: [Stéphane Bouchet - emn-fil](https://github.com/sbouchet/emn-fil/tree/master).

## Build and run

Requires a JDK (Java 8 or newer) and Maven. From the project directory:

```bash
mvn clean package
java -jar target/maven-archetype-simple-1.0-SNAPSHOT.jar
```

The build compiles the code, runs the tests, and creates the JAR in `target/`. The application prints `Hello World!`.
