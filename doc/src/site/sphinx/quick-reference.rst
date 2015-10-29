Quick Reference
***************

Here you can find a quick reference of existing elements, ready to use in your Ingestion deployment:

Sources
=======

*   Avro (Data serialization/RPC)
*   Thrift (Data serialization/RPC)
*   Exec (unix commands output)
*   JMS (queue system)
*   Spooling (watch for files changed in a folder)
*   Twitter Firehose 1% (experimental)
*   Kafka (queue system)
*   Netcat (data from a specified ip:port)
*   Sequence generator (generation of counter)
*   Syslog (data from syslog, TCP or UDP)
*   HTTP (data from HTTP POST or GET calls)
*   Stress (load generation for testing)
*   Scribe (adapter for Scribe ingestion system)
*   REST (calls to a REST service)
*   Redis (data from Redis Pub/Sub system).
*   IRC (IRC chat protocol)
*   SNMP traps (SNMP asynchronous notifications)

Transformations
===============

*   Flume Interceptors
*   Morphline Interceptors
*   Stratio Custom Interceptors


Channels
========

*   Memory channel
*   JDBC channel
*   Kafka channel
*   File channel
*   Spillable Memory channel
*   Pseudo Transaction channel

Sinks
=====

*   HDFS
*   Hive
*   Logger
*   Avro
*   Thrift
*   IRC
*   File Roll
*   Null
*   HBase
*   MorphlineSolr
*   ElasticSearch
*   Kite Dataset
*   Kafka
*   Custom
*   Cassandra
*   Druid
*   JDBC
*   Kafka
*   MongoDB
*   Stratio Decision
