# Software Testing Java

**Software Testing exam project at Federico II University to explain build and test automation with GitHub Actions, in a CI/CD context.**

The solution contains an HelloWorld Java class that return current local time and say "Hello World!"; also contains a JUnit Test class with Unit Test about HelloWorld class.

The Continuous Integration workflow pipeline job consists of the following steps:

- Checkout Source Repo  
- Setup JDK 11
- Install dependencies package from Maven Repo
- Build source code
- Run Unit Test

The Code Analysis workflow pipelint job, instead, consists of the following steps:
- Checkout Source Repo        
- Setup JDK 11      
- Cache SonarCloud packages       
- Install SonarCloud scanners
- Build, Analyze and collect Code Coverage

**The code quality result is:**

[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=nicolaceliento_sw_testing_java)](https://sonarcloud.io/summary/new_code?id=nicolaceliento_sw_testing_java)

