# DemoAnnotationSpring

This project demonstrates Spring dependency injection using annotations in Java.

## Structure
- `src/main/java/com/acc/lkm/springinjectiondemo/` — Main Java source files
- `beans.xml` — Spring bean configuration
- `pom.xml` — Maven build file
- `src/test/java/com/acc/lkm/springinjectiondemo/` — Unit tests

## CI/CD
A GitHub Actions pipeline is set up in `.github/workflows/maven.yml` to build and test the project on every push or pull request to the `master` branch.

## Build & Test
To build and test locally:

```
mvn clean package
mvn test
```

## Requirements
- Java 17+
- Maven 3.6+

## License
MIT
