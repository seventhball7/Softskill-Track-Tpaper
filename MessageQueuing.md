  # Message queuing
  So what is message queuing? Before we jump into this let us quickly know what queues are? So a queue is a line of things waiting to be processed or handled and they start from the beginning and are processed in sequential order. This means that a thing( message particularly here) that is at the starting position would be handled first and followed by it the rest of the things. Now let us know about message queuing. Message queuing means communication between applications by sending messages to each other. A message in message queuing refers to the data transferred between the sender and receiver's application. A message queue provides an asynchronous communications protocol which is a system that puts a message onto a message queue and does not require an immediate response to continuing processing. The best example of asynchronous communication is e-mail. 
  This model, known as asynchronous messaging prevents data loss and enables systems to continue to function if processes or connections fail. Now let us see the benefits of message queuing. 

  ### * Benefits :
      • Reliable message delivery:
        Using a message queue ensures that critical messages between applications will not be lost and that they will be only be delivered to the receiver once which results in avoiding data duplication.
      • Improved security: 
        A message queue may be able to identify and authenticate all messages, and also queue solutions that can be set to encrypt messages end-to-end. This can contribute to the overall security of the applications and/or infrastructure.  
      • Integrated file transfers: 
        Some message queue solutions include additional features, such as the ability to transfer files. This can be used as an alternative to FTP.
      • Versatility: 
        Message queue solutions can support multiple languages also support numerous application programming interfaces (APIs) and protocols.

  ### * Let us know the areas where message queuing is popular and used.
  Messaging queues can be used in areas that require high levels of security, fault tolerance, and accuracy, such as financial transaction processing, air-travel booking, or updating healthcare patient records. Message queues are also suited for integrating on-premises backend systems with cloud services. Message queues can also be used to enable applications and systems residing in different clouds to communicate, even if they are located in different regions of the globe. 
  They also work across various range of applications such as IoT and transaction system records. They also support various platforms such as virtual machines and containers. 
  ### Now let us look at the various popular message queuing tools:
    
  • Kafka

  • RabbitMQ

  • Amazon SQS 

  • Celery

  • ActiveMQ 

  # Enterprise Message Bus
  An Enterprise Message Bus is a middleware that works behind the scenes to support application to application communication. In other words, it is a tool used to distribute work among connected components of an application or applications. ESBs are designed to provide a uniform means of moving work, offering applications the ability to connect to the bus and subscribe to messages based on simple structural and business policy rules.  These solutions provide processes, protocols, and rules to facilitate secure data transfers and manage service-oriented applications. These tools can add new data and capabilities to existing enterprise applications. 
    
  ### * Benefits of an enterprise service bus
      • It makes it easy to change or add components.
      • Provides a convenient place to enforce security, logging, and monitoring.
      • Can provide load balancing to improve performance.
      • In case of component or resources fails, it provides fall over support too.

  ### * Let us look at the top Enterprise Service Bus Software:
  • IBM App ConnectTIBCO

  • Cloud Integration (including BusinessWorks and Scribe)

  • Software AG webMethods

  • Peregrine ConnectwebMethods Integration Server

  • Beats

  •Azure Service Bus

  • Apache Camel

  • NServiceBus
    
  • IBM Cloud Pak for Integration

  ### References:

  CloudAMQP.com

  aws.amazon.com

  searchapparchitecture.techtarget.com

    