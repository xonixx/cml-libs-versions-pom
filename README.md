# cml-libs-versions-pom

[![](https://jitpack.io/v/xonixx/cml-libs-versions-pom.svg)](https://jitpack.io/#xonixx/cml-libs-versions-pom)

Import scope pom.xml that captures actual CML libs versions

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
