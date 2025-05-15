# AMQP Questions

> a. What is amqp?

AMQP which stands for Advanced Message Queuing Protocol is a network protocol to handle messages between applications. AMQP enables applications to communicate with each other by sending messages between them. AMQP is commonly used for implementing message brokers for communication between programs, in this module using RabbitMQ.

> b. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for?


- The first `guest` is the username for authentication to the AMQP server.
- The second `guest` is the password for authentication to the AMQP server.
- `localhost:5672` specifies the host and port where the AMQP server is running.

So `guest:guest@localhost:5672` means connect to the AMQP server running on the local machine at port 5672, using 'guest' as both the username and password for authentication.
