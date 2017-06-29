# maven-quickstart-project

This tutorial shows how we can start a java project using Maven.
First, using a terminal, go to the directory where you want create the project.
 
    mvn archetype:generate

Type 'quick' to filter by projects with 'quick'in name. Some projects will be listed and the project 'maven-archetype-quickstart' with its respective number will be suggested. 

    Choose a number or apply filter (format: [groupId:]artifactId, case sensitive contains): 7: quick

    Choose archetype:
    1: internal -> org.apache.maven.archetypes:maven-archetype-quickstart (An archetype which contains a sample Maven project.)
    Choose a number or apply filter (format: [groupId:]artifactId, case sensitive contains): 1:

Maven will be ask for 'groupId', 'artifactId', 'version'and 'package'. 

    Define value for property 'groupId': br.com.learning   // type your groupId
    Define value for property 'artifactId': maven-quickstart-project  // type your project name
    Define value for property 'version' 1.0-SNAPSHOT: :    // Enter
    Define value for property 'package' br.com.learning: :   // Enter
    Confirm properties configuration:
    groupId: br.com.learning
    artifactId: maven-quickstart-project
    version: 1.0-SNAPSHOT
    package: br.com.learning
    Y: :    // Enter

Type 'ls' on terminal and you'll see the project folder created. Go inside the 'maven-archetype-quickstart' and there you will find the pom.xml file. This file will content the project dependencies.
And that's it! 

	
