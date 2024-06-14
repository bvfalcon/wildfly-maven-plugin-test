Demonstration of problem with wildfly-maven-plugin, goal dev

1) run command `mvn`

During executing will be created war file `wildfly-maven-plugin-test.war` and deployed into wildfly server (after downloading it) with runtime name `ROOT.war` (context path `/`). After performing integration tests (not included in demo project) wildfly server will be turned off.

2) run command `mvn clean package wildfly:dev`

Command ends with error: `ROOT.war` file not found

