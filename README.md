# kafka-study
To learn kafka and practice English. In this project, I will introduce the Kafka Project in Chinese and English. If you find some mistakes in grammar or knowledge, Welcome to correct.

**BEGIN**

Kafka传统定义：Kafka是一个分布式的基于发布/订阅模式的消息队列（Message Queue），主要应用于大数据实时处理领域。

The traditional definition of Kafka: Kafka is a distributed Message Queue based on publish/subscribe mode, which is mainly used in the field of real-time processing of big data.

发布/订阅：消息的发布者不会将消息直接发送给特定的订阅者，而是将发布的消息分为不同的类别，订阅者只接收感兴趣的消息。

publish/subscribe: the publisher of the message doesn't send messages to a specific subscriber,  but divide the publish message into different variety and the subscriber merely receive messages of their interest.

**application scenarios** 

缓冲/消峰：有助于控制和优化数据流经过系统的速度，解决生产消息和消费消息的处理速度不一致的情况。

buffer/avoid peak: It is contribute to control and optimize the speed at which data flows through the system, resolve cases when production and consumption messages are processed at inconsistent speeds.

解耦：允许你独立的扩展或修改两边的处理过程，只要确保它们遵守同样的接口约束。
