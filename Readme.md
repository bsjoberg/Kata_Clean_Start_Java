# Clean start for kata
This has one junit test and one behavior test (Cucumber) set up and passing. It uses Java 17 with Junit 5 and Cucumber 3.

Run `mvn test`

If you want sonarqube scanning the application then you will need to run a local sonarqube server and use the below command to run it. You will need to replace the token value with the one the you generate from the sonarqube application. 

``mvn clean verify sonar:sonar   -Dsonar.projectKey=Kata-Clean-Start-Java   -Dsonar.projectName='Kata-Clean-Start-Java'   -Dsonar.host.url=http://localhost:9000   -Dsonar.token=<insert_token_value>``