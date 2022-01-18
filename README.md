# cml-libs-versions-pom

[![](https://jitpack.io/v/xonixx/cml-libs-versions-pom.svg)](https://jitpack.io/#xonixx/cml-libs-versions-pom)

Import scope pom.xml that captures actual CML libs versions
  
This pom.xml captures versions for the following libs:
- [xonixx/java-utils](https://github.com/xonixx/java-utils)
- [xonixx/spring-web-requests-logging](https://github.com/xonixx/spring-web-requests-logging)
- [xonixx/hibernate-profiling-interceptor](https://github.com/xonixx/hibernate-profiling-interceptor)
- [xonixx/java-simple-profiling](https://github.com/xonixx/java-simple-profiling)

## Usage

In pom.xml:

```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.github.xonixx</groupId>
            <artifactId>cml-libs-versions-pom</artifactId>
            <version>v0.1.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
        ...
    </dependencies>
</dependencyManagement>
``` 

In pom.xml `<repositories>`

```xml
<repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
</repository>
``` 
