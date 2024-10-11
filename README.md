# seed-bdd-java
Seed Project for using Behavior Driven Development in Java

Uses Maven Cucumber Archetype to setup using [Gherkin](https://cucumber.io/docs/gherkin/reference/) syntax. Based off [Cucumber's Tutorial](https://cucumber.io/docs/guides/10-minute-tutorial/?lang=java)

Project Structure
- Gherkin features named .feature in 'src\test\resources'
- Step definitions inside 'src\java\'. Can be in different packages and subpackages within
  - Step definitions are actual java files
- A feature can have multiple step definition files and vice versa
  - Can reuse steps across features and other optimization

### Instructions
Standard maven setup
- Clone repo
- Run 'mvn clean install' for initial setup
- 'mvn test' to run all tests including BDD

### Future
- Create branches for specific types of projects like SpringBoot, REST APIs,...