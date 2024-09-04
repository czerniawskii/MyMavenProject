Maven.
Ivan Snytko
•
Aug 29
100 points
Due Sep 2, 4:59 PM
https://maven.apache.org/what-is-maven.html

https://maven.apache.org/users/index.html
https://maven.apache.org/repository/index.html
https://maven.apache.org/plugins/index.html








Move all projects to Maven. 
Build jar file and deploy to the local repository. mvn install
Add 1 Plugins.
Run mvn for different phases from the Maven lifecycle. Check the result.




MAVEN

- add libraries to our project - pom.xml

- run our tests without IDEA

- create jar



mavenrepository.com- remote

.m2 -  local




    validate - validate the project is correct and all necessary information is available
    compile - compile the source code of the project
    test - test the compiled source code using a suitable unit testing framework. These tests should not require the code be packaged or deployed
    package - take the compiled code and package it in its distributable format, such as a JAR.
    verify - run any checks on results of integration tests to ensure quality criteria are met
    install - install the package into the local repository, for use as a dependency in other projects locally
    deploy - done in the build environment, copies the final package to the remote repository for sharing with other developers and projects.











Questions for the exam that must be covered in this lecture.



What is M2_HOME? How to setup Maven?
What is settings.xml file for?
Describe maven project structure.
Describe maven lifecycle. Each step. 
What do you know about pom.xml file structure?
What do you know about local/remote repositories?
What is target directory?

How to work with maven plugin?
What Maven flags do you know?
How to work with maven profile?
