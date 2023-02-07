# kafka-producer-consumer
This code demonstrates a simple producer-consumer setup in Python

In this code, you first initialize the Kafka producer and consumer with the bootstrap server as localhost:9092. The producer can publish messages to a topic by calling the publish_message function. The consumer can then consume messages from the same topic by calling the consume_messages function. The consumer is set up to subscribe to the topic sample-topic, auto-commit offsets, and be part of the group sample-group. The consumer is set to receive messages and print them in real-time.
