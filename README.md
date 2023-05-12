# ScalaTest + TestNG
ScalaTest + TestNG provides integration support between ScalaTest and TestNG.

**Usage**

To use it for ScalaTest 3.2.16 and TestNG 7.5.x: 

SBT: 

```
libraryDependencies += "org.scalatestplus" %% "testng-7-5" % "3.2.16.0" % "test"
```

Maven: 

```
<dependency>
  <groupId>org.scalatestplus</groupId>
  <artifactId>testng-7-5_2.13</artifactId>
  <version>3.2.16.0</version>
  <scope>test</scope>
</dependency>
```

**Publishing**

Please use the following commands to publish to Sonatype: 

```
$ sbt +publishSigned
```
