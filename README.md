RS Components UI tests

This project is dedicated to testing RS Components UI via Selenium/Java/Cucumber-JVM facilities.

[[quick]]
== Quick start

. Clone project
. Open in IDEA
. Create new *JUNIT* run/debug configuration with the below parameters
Class = "steps.Runner"
_VM options = "-Dcucumber.options="--tags @E2ESearchByMenu"


You can use various **tags** like **@UITests** to run all scenarios from the feature file
**`mvn test -DcucumberOptions=" --tags @UITests"`**
OR
individual tests by specifying individual tags for example
**`mvn test -DcucumberOptions=" --tags @E2ESearchByMenu"`**





