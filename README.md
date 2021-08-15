# JAVA_JDBC_MySQL
Accessing MySQL Database using JDBC
Compilation and Preparation of JAR file

Java Program File Name: NameSearchApp.java
MySQL Driver: mysql-connector-java-5.1.45-bin.jar
Manifest File Name: NameSearchApp.mf
Contents of NameSearchApp.mf
    Manifest-Version: 1.0
    Main-Class: SwingSearchApp
    Class-Path: mysql-connector-java-5.1.45-bin.jar

Note: All the files in the same folder (NameSearchApp.java, NameSearchApp.mf, mysql-connector-java-5.1.45-bin.jar)

Compiling:
    javac NameSearchApp.java
Prparing the JAR file:
    jar cmf NameSearchApp.mf NameSearchApp.jar NameSearchApp.class

Running from Command Line:
    java -jar SwingSearchApp.jar
Running as Desktop App:
    Just double-click on the JAR file.
 
