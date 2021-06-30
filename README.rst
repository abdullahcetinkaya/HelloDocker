example.java.hello-docker
=======================

This is "Hello Docker" Example for Java.

The structure ``HelloDocker`` package is like this: ::

  example.java.hello-docker/
  |-- HelloDocker
  |   `-- Main.java
  |-- Manifest.txt
  `-- README.md

Compile class
-------------

For compile the main class for package, execute the follow command: ::

  javac HelloDocker/Main.java

This generate the ``Main.class`` file into ``HelloDocker`` directory.

Run class
---------

For run the main class for package, execute the follow command: ::

  java -cp . HelloDocker.Main

This show the ``Hello Docker :) `` message.

Create a JAR file
-----------------

For pack the main class for package as a JAR file, execute the follow command: ::

  jar cfme HelloDocker.jar Manifest.txt HelloDocker.Main HelloDocker/Main.class


Run a JAR file
--------------

For run the JAR file packed, execute the follow command: ::

  java -jar HelloDocker.jar

This show the ``Hello Docker :) `` message.

Reference
=========

- `java - How to run a JAR file - Stack Overflow <http://stackoverflow.com/questions/1238145/how-to-run-a-jar-file>`_.

- `Setting an Application's Entry Point (The Java™ Tutorials > Deployment > Packaging Programs in JAR Files) <http://docs.oracle.com/javase/tutorial/deployment/jar/appman.html>`_.
