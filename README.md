Ballerina File Library
=======================

  [![Build](https://github.com/ballerina-platform/module-ballerina-file/actions/workflows/build-timestamped-master.yml/badge.svg)](https://github.com/ballerina-platform/module-ballerina-file/actions/workflows/build-timestamped-master.yml)
  [![GitHub Last Commit](https://img.shields.io/github/last-commit/ballerina-platform/module-ballerina-file.svg)](https://github.com/ballerina-platform/module-ballerina-file/commits/master)
  [![Github issues](https://img.shields.io/github/issues/ballerina-platform/ballerina-standard-library/module/file.svg?label=Open%20Issues)](https://github.com/ballerina-platform/ballerina-standard-library/labels/module%2Ffile)
  [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
  [![codecov](https://codecov.io/gh/ballerina-platform/module-ballerina-file/branch/master/graph/badge.svg)](https://codecov.io/gh/ballerina-platform/module-ballerina-file)

This `file` library is one of the standard libraries of <a target="_blank" href="https://ballerina.io/">Ballerina</a> language.

This package provides APIs, which perform file, file path, and directory operations, and a `Directory Listener`, which is used to listen to a directory in the local file system.

For more information, go to the [`file` module](https://docs.central.ballerina.io/ballerina/file/latest).

For example demonstrations of the usage, go to [Ballerina By Examples](https://ballerina.io/learn/by-example/).

## Issues and Projects

Issues and Project tabs are disabled for this repository as this is part of the Ballerina Standard Library. To report bugs, request new features, start new discussions, view project boards, etc. please visit Ballerina Standard Library [parent repository](https://github.com/ballerina-platform/ballerina-standard-library). 

This repository only contains the source code for the package.

## Building from the Source

### Setting Up the Prerequisites

1. Download and install Java SE Development Kit (JDK) version 11 (from one of the following locations).
   * [Oracle](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)

   * [OpenJDK](https://adoptopenjdk.net/)

        > **Note:** Set the JAVA_HOME environment variable to the path name of the directory into which you installed JDK.
     
### Building the Source

Execute the commands below to build from source.

1. To build the library:

        ./gradlew clean build

2. To run the integration tests:

        ./gradlew clean test

3. To build the package without the tests:

        ./gradlew clean build -x test

4. To debug the tests:

        ./gradlew clean build -Pdebug=<port>
        
5. To debug the package with Ballerina language:
   
        ./gradlew clean build -PbalJavaDebug=<port>

6. Publish ZIP artifact to the local `.m2` repository:

        ./gradlew clean build publishToMavenLocal

7. Publish the generated artifacts to the local Ballerina central repository:
   
        ./gradlew clean build -PpublishToLocalCentral=true
        
8. Publish the generated artifacts to the Ballerina central repository:

        ./gradlew clean build -PpublishToCentral=true

## Contributing to Ballerina

As an open source project, Ballerina welcomes contributions from the community. 

For more information, go to the [contribution guidelines](https://github.com/ballerina-platform/ballerina-lang/blob/master/CONTRIBUTING.md).

## Code of Conduct

All contributors are encouraged to read the [Ballerina Code of Conduct](https://ballerina.io/code-of-conduct).

## Useful Links

* Discuss code changes of the Ballerina project in [ballerina-dev@googlegroups.com](mailto:ballerina-dev@googlegroups.com).
* Chat live with us via our [Slack channel](https://ballerina.io/community/slack/).
* Post all technical questions on Stack Overflow with the [#ballerina](https://stackoverflow.com/questions/tagged/ballerina) tag.
