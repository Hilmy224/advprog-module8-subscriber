## Tutorial 8 Questions

1. what is __amqp__?
+ AMQP stands for Advanced Message Queuing Protocol. It is an open standard application layer protocol for message-oriented middleware, enabling communication between different systems in a reliable and asynchronous manner.
2. what it means? `guest:guest@localhost:5672` , what is the first quest, and what is the second __guest__, and what is __localhost:5672__ is for? 
+  `guest:guest@localhost:5672` is used for establishing a connection to the AMQP server. This string follows a specific format, where each component has each of their roles in the connection process. 
+ First, the term `guest` represents the username used for authentication when connecting to the AMQP server. 
+ Similarly, the second occurrence of guest denotes the password associated with the provided username. These credentials are essential for verifying the identity of the client attempting to connect to the server.
+ Finally, `localhost:5672` specifies the address and port of the AMQP server which is run on a local machine.
+ Put it all together `guest:guest@localhost:5672` instructs the application to connect to the AMQP server using the specified username and password via port 5672 on the local machine.