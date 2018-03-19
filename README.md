## mplatform QA sample project for evaluating static analysis and code coverage tools
[![Coverage Status](https://coveralls.io/repos/github/yijinsu/test-cicd/badge.svg?branch=master)](https://coveralls.io/github/yijinsu/test-cicd?branch=master)

This is forked from https://spring.io/guides/gs/spring-boot-docker/ and cleaned.

The following tools are set up by mvn dependencies, reports or plugins:
```
Cobertura
Jacoco
Clover
Findbugs
SonarQube (Need to set up SonarQube docker container or a server and use mvn to post results)
```

Tools can be set up by forking this to your own repo and linking your github account to their accounts:
```
Coveralls ( maven dependency is also needed)
Codacy
```



To try any tools, please follow set up instructions here:
```
  https://mplatform.atlassian.net/wiki/spaces/mP/pages/343310631/Static+Analysis+and+Code+Coverage+Tools+Evaluation
```
All mvn dependencies and plugins for these tools are placed in pom.xml.

A sample Jenkins file is also provided to integrate jacoco and sonarqube in the CICD workflow.

### Authors
* **Karen Su** -  *Version 1* (03-19-2018)