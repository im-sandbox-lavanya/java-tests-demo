# Java Test Coverage Demo

This is a simple Java demo app to show test coverage results using Copilot and JaCoCo.

## How to Run

1. **Run Tests and Generate Coverage Report**
   ```powershell
   mvn clean test
   ```
   This will run the unit tests and generate a coverage report using JaCoCo.

2. **View Coverage Report**
   - After running tests, open `target/site/jacoco/index.html` in your browser to view the coverage results.

## Project Structure
- `src/main/java/com/example/Calculator.java`: Demo class
- `src/test/java/com/example/CalculatorTest.java`: Unit tests
- `pom.xml`: Maven config with JaCoCo and JUnit

## Requirements
- Java 11+
- Maven

---
Copilot can help you write more tests and improve coverage!
