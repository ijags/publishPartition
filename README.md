# Publish to partitioned RabbitMQ

## Spring Cloud Stream - RabbitMQ

This app sets hashkey in the message headers before sending the message to partitioned RabbitMQ queue. Thus enabling sequence for each consumer to process specific messageID in their partition. 
