[![License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

# Awesome Open-Source Contribs for Apache Kafka

A curated [list of awesome](https://github.com/topics/awesome-list) open-source frameworks, libraries, tools and examples for the [Apache Kafka](https://kafka.apache.org/) project.

Contributing to this project is easy! Just send a pull request and make the list growth!

## Table of contents

* [Client](#clients)
* [CLI/Tools](#cli--tools)
* [CDC](#change-data-capture)
* [Examples](#examples)
* [Site Reliability Tools](#site-reliability-tools)
* [Security / ACL](#security--acl)
* [Infrastructure](#infrastructure)
* [KafkaStreams](#kafkastreams)
* [Query/SQL](#query-sql)
* [REST API](#rest-api)
* [Replication](#replication)
* [Schema/Data](#schema--data)
* [Test](#test)
* [UI/Cluster Management](#uicluster-management)
* [Other Awesome Lists about Apache Kafka or Data Engineering](#other-awesome-lists-about-apache-kafka-or-data-engineering)
* [License](#license)

## Clients

* [librdkafka](https://github.com/edenhill/librdkafka): The Apache Kafka C/C++ library. 2-clause BSD license

## CLI / Tools

* [Kafkacat](https://github.com/edenhill/kafkacat): Generic command line non-JVM Apache Kafka producer and consumer. [librdkafka - Apache Kafka C driver library](https://github.com/edenhill/kafkacat/blob/master/LICENSE)

* [kafkacli](https://github.com/fhussonnois/kafkacli): CLI and Go Clients to manage Kafka components (Kafka Connect & SchemaRegistry). [Apache License 2.0](https://github.com/fhussonnois/kafkacli/blob/master/LICENSE)

## Change Data Capture

* [Debezium](https://github.com/debezium/debezium): Debezium is an open source project that provides a low latency data streaming platform for change data capture (CDC). [Apache License 2.0](https://github.com/debezium/debezium/blob/master/LICENSE.txt)

* [Maxwell](https://github.com/zendesk/maxwell): Maxwell's daemon, a mysql-to-json kafka producer. [Apache License 2.0](https://github.com/zendesk/maxwell/blob/master/LICENSE)

## Examples

* [Confluent Kafka Streams Examples](https://github.com/confluentinc/kafka-streams-examples): Demo applications and code examples for Apache Kafka's Streams API. [Apache License 2.0](https://github.com/confluentinc/kafka-streams-examples/blob/5.4.0-post/LICENSE)

* [Confluent Examples](https://github.com/confluentinc/examples): Apache Kafka and Confluent Platform examples and demos. [Apache License 2.0](https://github.com/confluentinc/examples/blob/5.4.0-post/LICENSE) 

* [kafka-examples](https://github.com/gwenshap/kafka-examples): Snippets and small examples demonstrating kafka features and configs. [Apache License 2.0](https://github.com/gwenshap/kafka-examples/blob/master/LICENSE)

## Site Reliability Tools

* [Datadog Kafka-kit](https://github.com/DataDog/kafka-kit): Kafka data mapping and recovery tools. [Apache License 2.0](https://github.com/DataDog/kafka-kit/blob/master/LICENSE)

* [kafka-monitoring-suite-demo-prometheus](https://github.com/streamthoughts/kafka-monitoring-suite-demo-prometheus): Demonstration on how to monitor Kafka using Prometheus and Grafana. [Apache License 2.0](https://github.com/streamthoughts/kafka-monitoring-suite-demo-prometheus/blob/master/LICENSE)

* [Linkedin - Burrow](https://github.com/linkedin/Burrow): Kafka Consumer Lag Checking. [Apache License 2.0](https://github.com/linkedin/Burrow/blob/master/LICENSE)

* [Linkedin - Cruise Control](https://github.com/linkedin/cruise-control): Cruise-control is the first of its kind to fully automate the dynamic workload rebalance and self-healing of a kafka cluster. It provides great value to Kafka users by simplifying the operation of Kafka clusters. [BSD 2-Clause "Simplified" License](https://github.com/linkedin/cruise-control/blob/master/LICENSE)

* [Linkedin - Xinfra Monitor](https://github.com/linkedin/kafka-monitor): Xinfra Monitor monitors the availability of Kafka clusters by producing synthetic workloads using end-to-end pipelines to obtain derived vital statistics - E2E latency, service availability & message loss rate. It reassigns partition & trigger preferred leader election to ensure each broker acts as leader of at least 1 partition of monitor topic.[Apache License 2.0](https://github.com/linkedin/kafka-monitor/blob/master/LICENSE)

* [Pinterest Doctor Kafka](https://github.com/pinterest/doctorkafka): DoctorKafka is a service for Kafka cluster auto healing and workload balancing. [Apache License 2.0](https://github.com/pinterest/doctorkafka/blob/master/LICENSE)

* [Uber - Chaperone ](https://github.com/uber/chaperone): As Kafka audit system, Chaperone monitors the completeness and latency of data stream. The audit metrics are persisted in database for Kafka users to quantify the loss of their topics if any. [Apache License 2.0](https://github.com/uber/chaperone/blob/master/LICENSE)

## Security / ACL

* [kafka-security-manager](https://github.com/simplesteph/kafka-security-manager): Manage your Kafka ACL at scale. [MIT License](https://github.com/simplesteph/kafka-security-manager/blob/master/LICENSE.txt)

* [Kafka Specs](https://github.com/streamthoughts/kafka-specs): Tool to ease and automate Apache Kafka cluster configuration management. [Apache License 2.0](https://github.com/streamthoughts/kafka-specs/blob/master/LICENSE)

## Infrastructure

* [Confluent Docker Images](https://github.com/confluentinc/cp-docker-images): Docker images for Confluent Platform. [Apache License 2.0](Apache License 2.0)

* [Confluent Platform Ansible](https://github.com/confluentinc/cp-ansible): Ansible playbooks for the Confluent Platform. [Apache License 2.0](https://github.com/confluentinc/cp-ansible/blob/5.4.0-post/LICENSE.md)

* [Strimzi](https://strimzi.io/): Strimzi provides a way to run an Apache Kafka cluster on Kubernetes in various deployment configurations. [Apache License 2.0](https://strimzi.io/LICENSE) 

## KafkaStreams

* [AzkarraStreams](https://github.com/streamthoughts/azkarra-streams): Azkarra Streams is a lightweight Java framework which makes easy to develop and operate Kafka Streams applications. [Apache License 2.0](https://github.com/streamthoughts/azkarra-streams/blob/master/LICENSE)

* [GoKa](https://github.com/lovoo/goka): Goka is a compact yet powerful distributed stream processing library for Apache Kafka written in Go. [BSD 3-Clause "New" or "Revised" License](https://github.com/lovoo/goka/blob/master/LICENSE)

* [Kafka Streams CEP](https://github.com/fhussonnois/kafkastreams-cep): Complex Event Processing on top of Kafka Streams
. [Apache License 2.0](https://github.com/fhussonnois/kafkastreams-cep/blob/master/LICENCE)

* [Kafka Streams Viz](https://github.com/zz85/kafka-streams-viz): A tool helps visualizing stream topologies by generating nice looking diagrams from a kafka stream topology descriptions.

## Query/SQL

* [ksqlDB](https://ksqldb.io/): The event streaming database purpose-built for stream processing applications. [Confluent Community License Agreement Version 1.0](https://github.com/confluentinc/ksql/blob/master/LICENSE)

## REST API

* [Kafka REST Proxy](https://github.com/confluentinc/kafka-rest): Confluent REST Proxy for Kafka. [Confluent Community License Agreement Version 1.0](https://github.com/confluentinc/kafka-rest/blob/master/LICENSE)

## Replication

* [Mirror Maker 2](https://github.com/apache/kafka/tree/trunk/connect/mirror): MM2 leverages the Connect framework to replicate topics between Kafka clusters. [Apache License 2.0](https://github.com/apache/kafka/blob/trunk/LICENSE)

* [Uber uReplicator](https://github.com/uber/uReplicator): Improvement of Apache Kafka Mirrormaker. [Apache License 2.0](https://github.com/uber/uReplicator/blob/master/LICENSE)

## Schema / Data

* [Confluent Schema Registry](https://github.com/confluentinc/schema-registry): Confluent Schema Registry for Kafka. [Confluent Community License Agreement Version 1.0](https://github.com/confluentinc/schema-registry/blob/master/LICENSE)

## Test

* [Mocked Streams](https://github.com/jpzk/mockedstreams): Scala DSL for Unit-Testing Processing Topologies in Kafka Streams. [Apache License 2.0](https://github.com/jpzk/mockedstreams/blob/master/LICENSE)

* [Kafka Junit](https://github.com/salesforce/kafka-junit): This library wraps Kafka's embedded test cluster, allowing you to more easily create and run integration tests using JUnit against a "real" kafka server running within the context of your tests. No need to stand up an external kafka cluster! [BSD 3-Clause "New" or "Revised" License](https://github.com/salesforce/kafka-junit/blob/master/LICENSE.txt)

* [kafka-streams-test-utils](https://kafka.apache.org/24/documentation/streams/developer-guide/testing.html): Testing Kafka Streams. Apache License 2.0

* [Test Container for Apache Kafka](https://www.testcontainers.org/modules/kafka/): Testcontainers can be used to automatically instantiate and manage Apache Kafka containers. More precisely Testcontainers uses the official Docker images for Confluent OSS Platform. [MIT License](https://github.com/testcontainers/testcontainers-java/blob/master/LICENSE)

## UI/Cluster Management

* [CMAK](https://github.com/yahoo/CMAK): CMAK (previously known as Kafka Manager) is a tool for managing Apache Kafka clusters. See below for details about the name change. [Apache License 2.0](https://github.com/yahoo/CMAK/blob/master/LICENSE)

* [Kafka HQ](https://github.com/tchiotludo/kafkahq): Kafka GUI for Apache Kafka to manage topics, topics data, consumers group, schema registry, connect and more. [Apache License 2.0](https://github.com/tchiotludo/kafkahq/blob/dev/LICENSE)

* [Kafdrop – Kafka Web UI](https://github.com/obsidiandynamics/kafdrop): Kafdrop is a web UI for viewing Kafka topics and browsing consumer groups. The tool displays information such as brokers, topics, partitions, consumers, and lets you view messages. [Apache License 2.0](https://github.com/obsidiandynamics/kafdrop/blob/master/LICENSE)

* [Kafka Eagle](https://www.kafka-eagle.org/): A easy and high-performance monitoring system, as well as offsets or metadata and other kafka information. [Apache License 2.0](https://github.com/smartloli/kafka-eagle/blob/master/LICENSE)

* [Kafkawize](https://kafkawize.com/): Kafkawize : A Self service Apache Kafka Topic Management tool/portal. A Web application which automates the process of creating and browsing Kafka topics, acls, schemas by introducing roles/authorizations to users of various teams of an org. [Apache License 2.0](https://github.com/muralibasani/kafkawize/blob/master/LICENSE)

* [Remora](https://github.com/zalando-incubator/remora): Kafka consumer lag-checking application for monitoring, written in Scala and Akka HTTP; a wrap around the Kafka consumer group command. Integrations with Cloudwatch and Datadog. Authentication recently added - [MIT License](https://github.com/zalando-incubator/remora/blob/master/LICENSE)

## Other Awesome Lists about Apache Kafka & Data Engineering
* [Awesome Open-Source Data Engineering](https://github.com/gunnarmorling/awesome-opensource-data-engineering/)
* [Awesome Data Engineering](https://github.com/igorbarinov/awesome-data-engineering)
* [infoslack/awesome-kafka](https://github.com/infoslack/awesome-kafka): This list is for anyone wishing to learn about Apache Kafka, but do not have a starting point.
* [dharmeshkakadia/awesome-kafka](https://github.com/dharmeshkakadia/awesome-kafka): Everything about Apache Kafka
* [Apache Kafka Ecosystem](https://cwiki.apache.org/confluence/display/KAFKA/Ecosystem)

## License
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
