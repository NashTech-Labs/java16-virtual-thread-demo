## Java16 Loom Example

This repository talks about the java16 virtual thread. We will first go through a simple virtual thread.
In second program we will implement the countDownLatch with virtual thread.

#### Prerequisites
Java Development Kit (JDK), version 16.
For ubuntu system please follow below statement. 
Set the java 16 path in .**bashrc** file. Make sure that only java 16 path is present in the file.

You a can check the java version with the following command.

For windows and mac system please set the java16 path in the environment variable.

`java -version`

It should return 16 as java version.

#### Maven

#### Getting the Project
Steps to start the project.

There are two main classes in the project. 
First, is the com.knoldus.VirtualThreadExample and second is com.knoldus.CountDownLatchExample class.

Steps to execute.

Run the following command in the directory where those classes exists.

`javac -d "classes"  "src/main/java/com/knoldus/CountDownLatchExample.java"`

`java  -classpath "classes"  "com.knoldus.CountDownLatchExample"`
