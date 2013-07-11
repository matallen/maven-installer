maven-installer
===============

installs anything in the src/main/resources folder into a maven repo (local or remote) in a consistent fashion

This project depends on the project: https://github.com/matallen/maven-resolver-plugin

Just download a red hat distribution (ie brms) and create a src/main/resources/<version> and extract the distribution zip into the version folder.

run the command "mvn clean install" from the maven-installer folder and it will install into the <maven.repository.url> as configured in the super.pom 
