# Chat-Box-with-3-Tier-Architecture-Using-RMI-in-Java
## Java Application for Group Chat using concepts of Java RMI.

## Table of Contents
### Introduction
The aim of the project is to build a chat application in which two or more users can enter in it, connected by same network. Users can send messages, emoji's, files, pictures and audio recordings which then goes to all the users logged in. Name of the user, login time and profile picture of user is saved in the database chat_java.

### Technologies
* IDE- NetBeans IDE 8.2
* Java 1.8.0_231
* Java Swing
* Java RMI
* MySQL
* XAMPP v3.2.4
* Setup
  * To run this project, install
    * NetBeans IDE
    * XAMPP
    * JDBC Driver for MySQL(Connector/J) version 8.0.18

### Specifications
* Important parts of project are

  * Project is divided into four sub-projects namely client, message, RMI and server.
  * First start the server(created by the network) from main->Main.java of server project.
  * Run main->Login.java of client project to login.
  * Higher level of Abstraction.
  * Good use of cohesion and coupling.
  * Use of socket programming of java.
  * Message sent from client to server then broadcasted to other clients.
