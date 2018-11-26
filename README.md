# awesome-pulsar [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]()

A curated list of awesome things about Apache Pulsar

> Apache Pulsar is a next-generation pub/sub messaging system developed at Yahoo. Pulsar was developed from the ground up to address several shortcomings of existing open source messaging systems and has been running in production for three years, powering critical applications like Yahoo! Mail, Yahoo! Finance, Yahoo! Sports, Flickr, the Gemini Ads Platform, and Sherpa, Yahoo’s distributed key value store. Pulsar was open sourced in late 2016 and is currently undergoing incubation under the auspices of the Apache Software Foundation. In this blog post, we will highlight key features of Pulsar that are available out of the box. ([Why Apache Pulsar](https://streaml.io/blog/why-apache-pulsar) )

![](https://streaml.io/media/img/blog/pulsar-partitions.png)


Here are cool features supported

- Geo-Replication
- Multi-Tenant
- Zero Data Loss
- Zero Rebalancing time
- Unified Queuing and Streaming Model
- Highly Scalable
- High Throughput
- Pulsar Proxy
- Functions

You can help by sending Pull Requests to add more information

## Table of Contents

- [Articles](#articles)
- [Comparisons](#comparisons)
- [Papers](#papers)
- [Presentations](#presentations)
- [Clients](#clients)
- [Tools](#tools)

### Articles

#### Overview

[Why Apache Pulsar? Part 1](https://streaml.io/blog/why-apache-pulsar)

[Apache Pulsar — Gentle Introduction](https://medium.com/@pckeyan/apache-pulsar-gentle-introduction-465ca6da0e18)

[Understanding How Apache Pulsar Works](https://jack-vanlightly.com/blog/2018/10/2/understanding-how-apache-pulsar-works)

[Apache Pulsar 2.0 Brings Enterprise-Class Scale, Speed and Functionality to Streaming Data Processing](https://insidebigdata.com/2018/06/24/apache-pulsar-2-0-brings-enterprise-class-scale-speed-functionality-streaming-data-processing/)

[Apache Pulsar Outperforms Apache Kafka by 2.5x on OpenMessaging Benchmark](https://www.businesswire.com/news/home/20180306005633/en/Apache-Pulsar-Outperforms-Apache-Kafka-2.5x-OpenMessaging)

#### Storage

[Introduction to Apache BookKeeper](https://streaml.io/blog/intro-to-bookkeeper)

[Building DistributedLog: High-performance replicated log service](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2015/building-distributedlog-twitter-s-high-performance-replicated-log-servic.html)

[DistributedLog at Twitter for High Performance Logging](https://www.infoq.com/news/2015/10/DistributedLog-Twitter-Logging)

[Code Analysis of Twitter’s DistributedLog](https://www.kiuwan.com/blog/analyzing_distributedlog_twitter-2/)

#### Messaging semantics

> Here at Streamlio, we prefer to use the term effectively-once over “exactly-once” because it highlights the fact that a messaging system needs to be able to detect and discard duplicate messages and to do so with a 100% degree of accuracy. We call this feature message deduplication.

[Effectively-once semantics in Apache Pulsar](https://streaml.io/blog/pulsar-effectively-once)

[How Apache Pulsar ensures no messages lost and no messages duplicated](https://streaml.io/blog/pulsar-effectively-once-end-to-end)

> No message loss, no duplicates, and ordering: taken together, they describe total order atomic broadcast (TOAB), which is known to be equivalent to consensus in distributed systems.

[Exactly once is NOT exactly the same](https://streaml.io/blog/exactly-once)

[Messaging, storage, or both?](https://streaml.io/blog/messaging-storage-or-both)

#### Functions

[Pulsar Functions overview](https://pulsar.apache.org/docs/latest/functions/overview/)

[Introducing Pulsar Functions](https://streaml.io/blog/pulsar-functions)

### Comparisions

[Comparing Pulsar and Kafka: unified queuing and streaming](https://streaml.io/blog/pulsar-streaming-queuing)

[Comparing Pulsar and Kafka: how a segment-based architecture delivers better performance, scalability, and resilience](https://streaml.io/blog/pulsar-segment-based-architecture)

![](https://streaml.io/media/img/blog/segment-vs-partition.png)

[A Technical Review of Kafka and DistributedLog](https://bookkeeper.apache.org/distributedlog/technical-review/2016/09/19/kafka-vs-distributedlog.html)

[Comparing LogDevice and Apache Pulsar](https://streaml.io/blog/comparing-logdevice-and-apache-pulsar)

### Papers

TBD

### Presentations

TBD

### Tools

TBD