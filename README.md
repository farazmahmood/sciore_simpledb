# sciore_simpledb


Ref : http://www.cs.bc.edu/~sciore/simpledb/


## Maven based build setup
Apache Maven is project management and build tool. SimpleDB has three components.
* **SimpleDB** -- DB implementation. 
* **SimpleClient** -- Simplified IJ client with test code to connect and execute commands against simpleDB (either networked or embedded) 
* **DerbyClient** -- Derby Client examples to run against DerbyDb. 

Defined pom.xml for each component, as well as one root such that single build command will build everything.

## Requirements
* [JDK](https://adoptium.net/temurin/releases/?version=23) (Preferably 23) 
* [Apache Maven](https://maven.apache.org/install.html)
* JAVA_HOME points to installed jdk 

[SDKMan](https://sdkman.io/) can be helpful for setting up jdk and other tool chains. 

## Building
### Clean
``` mvn clean ```

### Build
```mvn package```

## Artifacts 
jar files can be found under respective `target` folder.
