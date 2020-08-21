# hello-RMI
This repo shows how to run Java RMI offical tutorial using IntelliJ IDEA. Or you can choose to follow instrucitons in link below to run it using command line.

## [Official Guideline](https://docs.oracle.com/javase/8/docs/technotes/guides/rmi/hello/hello-world.html)

This tutorial shows you the steps to follow to create a distributed version of the classic Hello World program using Java Remote Method Invocation (Java RMI).

The distributed Hello World example uses a simple client to make a remote method invocation to a server which may be running on a remote host. The client receives the "Hello, world!" message from the server.

This tutorial has the following steps:

- Define the remote interface
- Implement the server
- Implement the client
- Compile the source files
- Start the Java RMI registry, server, and client

The files needed for this tutorial are:

- [`Hello.java`](example/hello/Hello.java) - a remote interface
- `Server.java` - a remote object implementation that implements the remote interface
- `Client.java` - a simple client that invokes a method of the remote interface

## Getting Started



## Possible Problems





## Reference

https://www.ibm.com/support/pages/unable-connect-remote-rmi-service-when-using-multi-homed-interface