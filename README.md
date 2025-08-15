# TASK 8: Run a Simple Java Maven Build Job in Jenkins
#### This repository contains the deliverables for Task 8 of the DevOps Internship. 
The objective of this task was to learn how to use Jenkins to build a simple Java application with Maven, a fundamental step in understanding Continuous Integration (CI).

### Objective
To configure a Jenkins Freestyle job to build a basic Java "Hello World" application using Apache Maven.

### Files and Folder Structure
The project has the following structure, which follows Maven's standard conventions:

hello-java-maven/  
└── src/
    └── main/
        └── java/
            └── HelloWorld.java
└── pom.xml


#### HelloWorld.java: The simple Java application that prints a message to the console.

#### pom.xml: The Maven Project Object Model file, which contains project information and build instructions.

#### What I Did
Created the Java Application: I created the HelloWorld.java and pom.xml files with the specified content.

#### Started Jenkins: I launched a Jenkins instance using Docker.

#### Configured Jenkins: In Jenkins, I navigated to Global Tool Configuration and added an installation of Apache Maven.

#### Created a Jenkins Job: I created a new Freestyle project, configured it to use Maven, and set the build goal to clean package.

##### Built the Job: I manually triggered the build job in Jenkins.

#### Verified and Captured Output: The build was successful, and I have included a screenshot of the console output showing BUILD SUCCESS.

### Deliverables
The source code for the "Hello World" Java application (HelloWorld.java) and the Maven configuration file (pom.xml).

A screenshot of the successful Jenkins console output, demonstrating that the build job ran correctly.

## Jenkins Installation & Access
I installed Jenkins using a Docker command: docker run -p 8080:8080 jenkins/jenkins:lts.

This command exposes the Jenkins web interface on port 8080 of my local machine.

The Jenkins instance can be accessed via a web browser at http://localhost:8080.
