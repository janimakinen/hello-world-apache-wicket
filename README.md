# Hello World for Apache Wicket 6.31.0-SNAPSHOT

This is a simple hello world project for the Wicket-tech. Clone this and do the steps from 1,2,3 and you should see a hello world appear.

## How to use?
1. Clone this and import import this folder as a Maven project into your Eclipse 2020 IDE
2. Navigate in Eclipse to the file src/test/java/com/janimakinen/helloworld/Start.java
3. Press the run button and open your browser at http://localhost:8080

## Prerequisites:
	Java installed. (Java 1.8+)
	Maven installed. (Maven 3.6+) 
	Eclipse installed. (Version from year 2020 and up)

## More information

- What is Maven?
	- It is used to download all the parts (including the web server) required to run the application. See more here: https://maven.apache.org/guides/getting-started/index.html
- What is Eclipse?
	- An open source integrated development environment for multiple programming languages. Download it from here: https://www.eclipse.org/downloads/
- Is there an installer for Maven?
	- No you just unzip the binaries and add the folder into your PATH. It's a bit funky. See: https://stackoverflow.com/questions/26609922/maven-home-mvn-home-or-m2-home You don't need to define MAVEN_HOME, just the path to your bin like so: C:\Program Files\apache-maven-3.6.3\bin
- If I want to use another version of wicket, what do I do?
	- Go here: https://wicket.apache.org/start/quickstart.html and change the version. The executable command will adapt itself to your version number.

## NIST Security vulnerabilities

CVE-2019-17571
See: https://nvd.nist.gov/vuln/detail/CVE-2019-17571

There is currently no fix for the above ^