##CS414 A1 Maven Starter##

This is a Maven starter project for CSU's CS414 assignment A1 (Fall 2014). Assuming the submission guidelines remain similar, the project can be easily repurposed for other assignments.

###Usage###
1. Change the *csu.eID* property in the pom to match your CSU eID. Alternatively you can provide this value via command line (e.g., *mvn package -Dcsu.eID=bob*)
2. Update the package names and directories to reflect your eID OR simply remove the source code along with package directories and start over. Just make sure the directory structure conforms to standard [Maven layout] (https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html). (I originally included the class stubs to make sure the build works, but presumably you'll be iteratively creating your own classes as you go through the TDD process.)
3. Run '*mvn package*' to build the project.

The build will run all your tests and generate either a jar or zip in the target directory (format can be specified in the pom via the *csu.file.format* property). The archive will contain all your sources, tests, and any resources placed in /src/main/resources or /src/test/resources (e.g., 'overview.txt'). As far as I know, this conforms to the submission requirements, but if you find out otherwise, please let me know or submit a pull request.

###Disclaimer###
If you decide to use this project, you're doing so at your own risk. I take absolutely no responsibility for your grade. Before submitting, please be sure to check that resulting archive conforms to the submission requirements, that the source code inside the archive compiles, and that the tests run with JUnit from command line.

The project was tested in the following environment:

* Maven 3.2.2
* OSX 10.9.4
* Java 1.8
* IntelliJ 13
