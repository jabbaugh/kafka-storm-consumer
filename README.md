kafka-storm-consumer
==============

Example of a Kafka Storm Consumer that dies when attempting to consume using
data that is Snappy Compressed.

Dependencies
==============
You need storm (http://storm-project.net/) to run the topology

Setting Env Vars
==============
export KAFKA_DOMAIN=127.0.0.1
export KAFKA_PORT=9092
export KAFKA_TOPIC=test

Package and Run
==============
mvn package
storm jar storm.example.trident.ExampleTopology
