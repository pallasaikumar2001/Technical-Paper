# Messaging Queues:

Message queues enable communication between various system components, which makes them crucial to system architecture. Because they serve as buffers, messages can be sent and received asynchronously, enabling systems to function normally even if certain components are temporarily or slowly unavailable.
## Usage of Messaging Queues:

**Background Task Processing:** The tasks that don't need to be processed immediately like Sending emails, Video Processing Service can be handled using a Queue.

**Load Balancing for Web Applications:** Messaging queues help distribute incoming requests among available servers, improving the performance of web applications.

**Server Health Monitoring:** A system monitoring tool can push alerts to a queue when a server’s health metrics go beyond a threshold, triggering alerts or automated actions.

These are some important Messaging Queues.

## Popular tools in Messaging Queues:


In Computer world the Messaging Queue Tools play an important role in seamless communication between various system components.

1. Google Cloud Pub/Sub.
2. Azure Service Bus.
3. Amazon SQS (Simple Queue Service).
4. Kafka.
5. RabbitMQ.
6. Apache ActiveMQ.

These are the top 6 popular tools in Messaging Queues.

## Enterprise Messaging Bus:

"Enterprising Message Bus (EBS)" is called an "Enterprise Service Bus (ESB)". It is an architecture that enables different applications within the organization to communicate with each other effectively. Enterprise Messaging Bus's main purpose is to "Handle conflicts between service components that need to communicate."

###References:
https://aws.amazon.com/message-queue/
https://www.geeksforgeeks.org/message-queues-system-design/
https://icepanel.medium.com/top-6-message-queues-for-distributed-architectures-a3cbabf08993
