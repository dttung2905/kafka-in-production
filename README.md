# kafka-in-production

![HitCount](http://hits.dwyl.com/dttung2905/kafka-in-production.svg)
![license](https://img.shields.io/github/license/dttung2905/kafka-in-production)
![stars](https://img.shields.io/github/stars/dttung2905/kafka-in-production)

Curious to know how big companies are operating their kafka fleet in production? This might be the repo for you:

- **What** are the issues encountered when running kafka in production? 📝
- **How** other organisations attempt to solve the issues? 🛠️
- **Why** certain approaches are adopted over others? :balance_scale:
- **What** can we learn for our own use case?

## Table of Contents

1. [Adobe](#adobe)
2. [Agoda](#agoda)
3. [Airbnb](#airbnb)
4. [Apple](#apple)
5. [AppsFlyer](#appsflyer)
6. [Bloomberg](#bloomberg)
7. [Bolt](#bolt)
8. [Booking.com](#bookingcom)
9. [Brex](#brex)
10. [Cloudflare](#cloudflare)
11. [Coinbase](#coinbase)
12. [Criteo](#criteo)
13. [Datadog](#datadog)
14. [Deliveroo](#deliveroo)
15. [GoTo](#goto)
16. [Grab](#grab)
17. [Honeycomb](#honeycomb)
18. [LinkedIn](#linkedin)
19. [Lyft](#lyft)
20. [Morgan Stanley](#morgan-stanley)
21. [Netflix](#netflix)
22. [Pinterest](#pinterest)
23. [Riskified](#riskified)
24. [Robinhood](#robinhood)
25. [Slack](#slack)
26. [Stripe](#stripe)
27. [Uber](#uber)
28. [Wise](#wise)
29. [Wix](#wix)
30. [Yelp](#yelp)
31. [Zalando](#zalando)
32. [Zopa Bank](#zopa-bank)

## Adobe

- [How Adobe Experience Platform Pipeline Became the Cornerstone of In-Flight Processing for Adobe](https://blog.developer.adobe.com/how-adobe-experience-platform-pipeline-became-the-cornerstone-of-in-flight-processing-for-adobe-51c0e0a91521) - `2019` - :books:
- [Moving Beyond Newtonian Reductionism in the Management of Large-Scale Distributed Systems, Part 2](https://blog.developer.adobe.com/moving-beyond-newtonian-reductionism-in-the-management-of-large-scale-distributed-systems-part-2-35c3f91f96e3) - `2019` - :books:
- [Adobe Experience Platform’s Streaming Sources and Destinations Overview and Architecture](https://blog.developer.adobe.com/adobe-experience-platforms-streaming-sources-and-destinations-overview-and-architecture-ba0b4d3e7ded) - `2019` - :books:
- [Wins from Effective Kafka Monitoring at Adobe: Stability, Performance, and Cost Savings](https://blog.developer.adobe.com/wins-from-effective-kafka-monitoring-at-adobe-stability-performance-and-cost-savings-a3ecb701ee5b) - `2019` - :books:
- [Creating Adobe Experience Platform Pipeline with Kafka](https://blog.developer.adobe.com/creating-the-adobe-experience-platform-pipeline-with-kafka-4f1057a11ef) - `2018` - :books:

## Agoda

- [How Agoda manages 1.5 Trillion Events per day on Kafka](https://medium.com/agoda-engineering/how-agoda-manages-1-5-trillion-events-per-day-on-kafka-f0a27fc32ecb) - `2021` - :books:
- [Adding Time Lag to Monitor Kafka Consumer](https://medium.com/agoda-engineering/adding-time-lag-to-monitor-kafka-consumer-2c626fa61cfc) - `2021` - :books:
- [How our data scientists' petabytes of data is ingested into Hadoop (from Kafka)](https://medium.com/agoda-engineering/ingesting-petabytes-of-data-per-week-into-hadoop-from-kafka-457718cc308c) - `2021` - :books:

## Airbnb

- [Migrating Kafka transparently between Zookeeper clusters](https://medium.com/airbnb-engineering/migrating-kafka-transparently-between-zookeeper-clusters-e68a75062f65) - `2021` - :books:

## Apple

- [Balance Kafka Cluster with Zero Data Movement](https://www.confluent.io/events/kafka-summit-london-2023/balance-kafka-cluster-with-zero-data-movement/) - `2023` - :studio_microphone:
- [Experiences Operating Apache Kafka® at Scale](https://www.confluent.io/kafka-summit-ny19/experiences-operating-apache-kafka-at-scale/) - `2019` - :studio_microphone:
- [Kafka as a Service A Tale of Security and Multi Tenancy](https://www.confluent.io/blog/rounding-up-kafka-summit-london-2018/) - `2018` - :studio_microphone:

## AppsFlyer
- [Four Crucial Steps to Take Before Changing Kafka Partition Key at Scale](https://medium.com/appsflyerengineering/four-crucial-steps-to-take-before-changing-kafka-partition-key-at-scale-3c2e553c73b2) - `2023` - :books:
- [Kafka Lag Monitoring For Human Beings](https://www.confluent.io/resources/kafka-summit-2020/kafka-lag-monitoring-for-human-beings/) - `2020` - :studio_microphone:
- [Apache Kafka Lag Monitoring at AppsFlyer](https://www.confluent.io/blog/kafka-lag-monitoring-and-metrics-at-appsflyer/) - `2020` - :books:
- [Managing your Kafka in an explosive growth environment](https://www.youtube.com/watch?v=tjjeaCtsw_M) - `2019` - :studio_microphone:

## Bloomberg

- [Fully-Managed, Multi-Tenant Kafka Clusters: Tips, Tricks, and Tools](https://www.confluent.io/resources/kafka-summit-2020/fully-managed-multi-tenant-kafka-clusters-tips-tricks-and-tools/) - `2022` - :studio_microphone:

## Bolt

- [Using Apache Kafka and ksqlDB for Data Replication at Bolt](https://www.youtube.com/watch?v=ymx55BA8eQU&ab_channel=Confluent) - `2021` - :studio_microphone:
- [How Bolt Has Adopted Change Data Capture with Confluent Platform](https://www.confluent.io/blog/how-bolt-adopted-cdc-with-confluent-for-real-time-data-and-analytics/) - `2020` - :books:
- [Kewei Shang](https://medium.com/bolt-labs/streaming-vitess-at-bolt-f8ea93211c3f) - `2020` - :books:

## Booking.com

- [Data Streaming Ecosystem Management at Booking.com](https://www.confluent.io/kafka-summit-sf18/data-streaming-ecosystem-management/) - `2018` - :books:

## Brex

- [Transactional Events Publishing At Brex](https://medium.com/brexeng/transactional-events-publishing-at-brex-66a5984f0726) - `2022` - :books:

## Cloudflare

- [Intelligent, automatic restarts for unhealthy Kafka consumers](https://blog.cloudflare.com/intelligent-automatic-restarts-for-unhealthy-kafka-consumers/) - `2023` - :books:
- [Using Apache Kafka to process 1 trillion inter-service messages](https://blog.cloudflare.com/using-apache-kafka-to-process-1-trillion-messages/) - `2022` - :books:

## Coinbase

- [Kafka infrastructure renovation at Coinbase](https://www.coinbase.com/blog/kafka-infrastructure-renovation) - `2022` - :books:
- [How we scaled data streaming at Coinbase using AWS MSK](https://www.coinbase.com/blog/how-we-scaled-data-streaming-at-coinbase-using-aws-msk) - `2021` - :books:

## Criteo

- [Managing Kafka and Data Streams at Criteo](https://medium.com/criteo-engineering/managing-kafka-and-data-streams-at-criteo-566ffbfda6ba) - `2023` - :books:
- [Upgrading Kafka on a large infra, or: when moving at scale requires careful planning](https://medium.com/criteo-engineering/upgrading-kafka-on-a-large-infra-3ee99f56e970) - `2019` - :books:
- [How Criteo is managing one of the largest Kafka Infrastructure in Europe](https://www.slideshare.net/RicardoPaiva17/how-criteo-is-managing-one-of-the-largest-kafka-infrastructure-in-europe) - `2019` - :books:

## Datadog

- [Running Production Kafka Clusters in Kubernetes](https://www.confluent.io/kafka-summit-lon19/running-production-kafka-clusters-kubernetes/) - `2019` - :studio_microphone:

## Deliveroo

- [Improving Stream Data Quality With Protobuf Schema Validation](https://deliveroo.engineering/2019/02/05/improving-stream-data-quality-with-protobuf-schema-validation.html) - `2019` - :books:

## GoTo

- [Sink Kafka Messages to ClickHouse Using 'ClickHouse Kafka Ingestor'](https://blog.gojek.io/sink-kafka-messages-to-clickhouse-using-clickhouse-kafka-ingestor/) - `2022` - :books:
- [When Kafka Went Offshore](https://blog.gojek.io/when-kafka-went-offshore/) - `2021` - :books:
- [Enhancing Ziggurat - The Backbone Of Gojek's Kafka Ecosystem](https://blog.gojek.io/enhancing-ziggurat-the-backbone-of-gojeks-kafka-ecosystem/) - `2021` - :books:
- [Handling Dead Letters in a Streaming System](https://blog.gojek.io/handling-dead-letters-in-a-streaming-system/) - `2020` - :books:
- [How Kafka Solved a Culture Problem at Gojek](https://blog.gojek.io/how-kafka-solved-a-culture-problem-at-gojek/) - `2019` - :books:
- [Fronting : An Armoured Car for Kafka Ingestion](https://blog.gojek.io/fronting-an-armoured-car-for-kafka-ingestion/) - `2018` - :books:
- [Sakaar: Taking Kafka data to cloud storage at GO-JEK](https://blog.gojek.io/sakaar-taking-kafka-data-to-cloud-storage-at-go-jek/) - `2018` - :books:

## Grab

- [Zero trust with Kafka](https://engineering.grab.com/zero-trust-with-kafka) - `2022` - :books:
- [How Kafka Connect helps move data seamlessly](https://engineering.grab.com/kafka-connect) - `2022` - :books:
- [Exposing a Kafka Cluster via a VPC Endpoint Service](https://engineering.grab.com/exposing-kafka-cluster) - `2022` - :books:
- [Detect Fraud Successfully with GrabDefence!](https://www.confluent.io/events/kafka-summit-apac-2021/detect-fraud-successfully-with-grabdefence/) - `2021` - :studio_microphone:
- [Optimally Scaling Kafka Consumer Applications](https://engineering.grab.com/optimally-scaling-kafka-consumer-applications) - `2020` - :books:

## Honeycomb

- [Scaling Telemetry Systems with Streaming](https://www.usenix.org/conference/srecon23americas/presentation/fong-jones) - `2023` - :studio_microphone:
- [Lessons Learned From the Migration to Confluent Kafka](https://www.honeycomb.io/blog/kafka-migration-lessons-learned) - `2021` - :books:
- [Scaling Kafka at Honeycomb](https://www.honeycomb.io/blog/scaling-kafka-observability-pipelines) - `2021` - :books:
- [Bitten by a Kafka Bug - Postmortem](https://www.honeycomb.io/blog/bitten-by-a-kafka-bug-postmortem) - `2019` - :books:

## LinkedIn

- [Load-balanced Brooklin Mirror Maker: Replicating large-scale Kafka clusters at LinkedIn](https://engineering.linkedin.com/blog/2022/load-balanced-brooklin-mirror-maker--replicating-large-scale-kaf) - `2022` - :books:
- [TopicGC: How LinkedIn cleans up unused metadata for its Kafka clusters](https://engineering.linkedin.com/blog/2022/topicgc_how-linkedin-cleans-up-unused-metadata-for-its-kafka-clu) - `2022` - :books:
- [How LinkedIn customizes Apache Kafka for 7 trillion messages per day](https://engineering.linkedin.com/blog/2019/apache-kafka-trillion-messages) - `2019` - :books:
- [URP? Excuse You! The Three Metrics You Have to Know](https://www.confluent.io/kafka-summit-london18/urp-excuse-you-the-three-metrics-you-have-to-know/) - `2018` - :studio_microphone:
- [Test Strategy for Samza/Kafka Services](https://engineering.linkedin.com/blog/2017/04/test-strategy-for-samza-kafka-services) - `2017` - :books:
- [Kafka Ecosystem at LinkedIn](https://engineering.linkedin.com/blog/2016/04/kafka-ecosystem-at-linkedin) - `2016` - :books:
- [Kafkaesque Days at LinkedIn – Part 1](https://engineering.linkedin.com/blog/2016/05/kafkaesque-days-at-linkedin--part-1) - `2016` - :books:
- [How We’re Improving and Advancing Kafka at LinkedIn](https://engineering.linkedin.com/apache-kafka/how-we_re-improving-and-advancing-kafka-linkedin) - `2015` - :books:

## Lyft

- [Building an Adaptive, Multi-Tenant Stream Bus with Kafka and Golang](https://eng.lyft.com/building-an-adaptive-multi-tenant-stream-bus-with-kafka-and-golang-5f1410bf2b40) - `2020` - :books:
- [Can Kafka Handle a Lyft Ride?](https://www.confluent.io/resources/kafka-summit-2020/can-kafka-handle-a-lyft-ride/) - `2020` - :studio_microphone:
- [Operating Apache Kafka Clusters 24/7 Without A Global Ops Team](https://eng.lyft.com/operating-apache-kafka-clusters-24-7-without-a-global-ops-team-417813a5ce70) - `2019` - :books:
- [Bulletproof Apache Kafka® with Fault Tree Analysis](https://www.confluent.io/kafka-summit-ny19/bulletproof-kafka-with-fault-tree-analysis/) - `2019` - :studio_microphone:
- [Production Ready Kafka on Kubernetes](https://www.confluent.io/kafka-summit-san-francisco-2019/production-ready-kafka-on-kubernetes/) - `2019` - :studio_microphone:

## Morgan Stanley

- [Consistent, High-throughput, Real-time Calculation Engines Using Kafka Streams](https://www.confluent.io/events/kafka-summit-london-2023/consistent-high-throughput-real-time-calculation-engines-using-kafka-streams/) - `2023` - :studio_microphone:

## Netflix

- [Featuring Apache Kafka in the Netflix Studio and Finance World](https://www.confluent.io/blog/how-kafka-is-used-by-netflix/) - `2020` - :books:
- [Inca — Message Tracing and Loss Detection For Streaming Data @Netflix](https://netflixtechblog.medium.com/inca-message-tracing-and-loss-detection-for-streaming-data-netflix-de4836fc38c9) - `2019` - :books:
- [Evolution of the Netflix Data Pipeline](https://netflixtechblog.com/evolution-of-the-netflix-data-pipeline-da246ca36905) - `2016` - :books:
- [Kafka Inside Keystone Pipeline](https://netflixtechblog.com/kafka-inside-keystone-pipeline-dd5aeabaf6bb) - `2016` - :books:

## Pinterest

- [Lessons Learned from Running Apache Kafka at Scale at Pinterest](https://www.confluent.io/blog/running-kafka-at-scale-at-pinterest/) - `2021` - :books:
- [How Pinterest runs Kafka at scale](https://medium.com/pinterest-engineering/how-pinterest-runs-kafka-at-scale-ff9c6f735be) - `2018` - :books:
- [Open sourcing DoctorKafka: Kafka cluster healing and workload balancing](https://medium.com/pinterest-engineering/open-sourcing-doctorkafka-kafka-cluster-healing-and-workload-balancing-e51ad25b6b17) - `2017` - :books:

## Riskified

- [How to Manage Schemas and Handle Standardization](https://medium.com/riskified-technology/how-riskified-manages-schemas-and-handles-standardization-fda9eb236e28) - `2023` - :books:
- [How to Roll Your Kafka Cluster With Zero Downtime and No Data Loss](https://medium.com/riskified-technology/how-to-roll-your-kafka-cluster-with-zero-downtime-and-no-data-loss-770fd0a35971) - `2023` - :books:
- [Know Your Limits: Cluster Benchmarks](https://medium.com/riskified-technology/know-your-limits-cluster-benchmarks-ecc6c3c77574) - `2022` - :books:
- [Let’s Make Your CFO Happy; A Practical Guide for Kafka Cost Reduction](https://www.confluent.io/en-gb/events/kafka-summit-london-2022/lets-make-your-cfo-happy-a-practical-guide-for-kafka-cost-reduction/) - `2022` - :studio_microphone:
- [From AWS CloudFormation to Terraform: Migrating Apache Kafka](https://medium.com/riskified-technology/from-aws-cloudformation-to-terraform-migrating-apache-kafka-32bdabdbaa59) - `2021` - :books:

## Robinhood

- [Tackling Kafka, with a Small Team](https://www.confluent.io/kafka-summit-san-francisco-2019/tackling-kafka-with-a-small-team/) - `2019` - :studio_microphone:

## Slack

- [Building Self-driving Kafka clusters using open source components](https://slack.engineering/building-self-driving-kafka-clusters-using-open-source-components/) - `2022` - :books:

## Stripe

- [6 Nines: How Stripe keeps Kafka highly-available across the globe](https://www.confluent.io/events/kafka-summit-london-2022/6-nines-how-stripe-keeps-kafka-highly-available-across-the-globe/) - `2022` - :studio_microphone:

## Uber

- [Securing Kafka® Infrastructure at Uber](https://www.uber.com/en-SG/blog/securing-kafka-infrastructure-at-uber/) - `2022` - :books:
- [Real-Time Exactly-Once Ad Event Processing with Apache Flink, Kafka, and Pinot](https://www.uber.com/en-SG/blog/real-time-exactly-once-ad-event-processing/) - `2021` - :books:
- [Introducing uGroup: Uber’s Consumer Management Framework](https://www.uber.com/en-SG/blog/introducing-ugroup-ubers-consumer-management-framework/) - `2021` - :books:
- [Disaster Recovery for Multi-Region Kafka at Uber](https://www.uber.com/en-SG/blog/kafka/) - `2020` - :books:
- [Kafka Cluster Federation at Uber](https://www.confluent.io/kafka-summit-san-francisco-2019/kafka-cluster-federation-at-uber/) - `2019` - :studio_microphone:
- [Building Reliable Reprocessing and Dead Letter Queues with Apache Kafka](https://www.uber.com/en-SG/blog/reliable-reprocessing/) - `2018` - :books:
- [Introducing Chaperone: How Uber Engineering Audits Apache Kafka End-to-End](https://www.uber.com/en-SG/blog/chaperone-audit-kafka-messages/) - `2016` - :books:
- [uReplicator: Uber Engineering’s Robust Apache Kafka Replicator](https://www.uber.com/blog/ureplicator-apache-kafka-replicator/) - `2016` - :books:

## Wise

- [Streaming Infrastructure at Wise](https://www.confluent.io/events/kafka-summit-london-2023/streaming-infrastructure-at-wise/) - `2023` - :studio_microphone:
- [Rack awareness in Kafka Streams](https://medium.com/wise-engineering/rack-awareness-in-kafka-streams-448d7e5225a3) - `2022` - :books:
- [Teamwork: Implementing a Kafka retry strategy at Wise](https://medium.com/wise-engineering/teamwork-implementing-a-kafka-retry-strategy-at-wise-82e0887e243b) - `2021` - :books:
- [Running Kafka in Kubernetes, Part 1: Why we migrated our Kafka clusters to Kubernetes.](https://medium.com/wise-engineering/running-kafka-in-kubernetes-part-1-why-we-migrated-our-kafka-clusters-to-kubernetes-722101a2e751) - `2021` - :books:
- [Running Kafka in Kubernetes, Part 2: How we migrated our Kafka clusters to Kubernetes.](https://medium.com/wise-engineering/running-kafka-in-kubernetes-part-2-how-we-migrated-our-kafka-clusters-to-kubernetes-69174cea1559) - `2021` - :books:
- [Securing Kafka with SPIFFE at TransferWise - Jonathan Oddy, Levani Kokhreidze](https://www.youtube.com/watch?v=4pfY0uFW7yk&ab_channel=CNCF%5BCloudNativeComputingFoundation%5D) - `2020` - :studio_microphone:
- [Achieving high availability with stateful Kafka Streams applications](https://medium.com/wise-engineering/achieving-high-availability-with-stateful-kafka-streams-applications-cba429ca7238) - `2018` - :books:

## Wix

- [4 Steps for Kafka Rebalance - Notes From the Field](https://www.wix.engineering/post/4-steps-for-kafka-rebalance-notes-from-the-field) - `2021` - :books:
- [Wix’s Journey Into Data Streams](https://www.wix.engineering/post/wix-s-journey-into-data-streams) - `2021` - :books:
- [Building a High-level SDK for Kafka: Greyhound Unleashed](https://www.wix.engineering/post/building-a-high-level-sdk-for-kafka-greyhound-unleashed) - `2020` - :books:

## Yelp

- [Kafka on PaaSTA: Running Kafka on Kubernetes at Yelp (Part 1 - Architecture)](https://engineeringblog.yelp.com/2021/12/kafka-on-paasta-part-one.html) - `2021` - :books:
- [Streams and Monk – How Yelp is Approaching Kafka in 2020](https://engineeringblog.yelp.com/2020/01/streams-and-monk-how-yelp-approaches-kafka-in-2020.html) - `2020` - :books:
- [Billions of Messages a Day – Yelp’s Real-time Data Pipeline](https://www.confluent.io/es-es/kafka-summit-nyc17/billions-messages-day-yelps-real-time-data-pipeline/) - `2017` - :studio_microphone:

## Zalando

- [Rock Solid Kafka and ZooKeeper Ops on AWS](https://engineering.zalando.com/posts/2018/01/rock-solid-kafka.html) - `2018` - :books:
- [Many-to-Many Relationships Using Kafka](https://engineering.zalando.com/posts/2018/05/many-to-many-using-kafka.html) - `2018` - :books:
- [Event First Development - Moving Towards Kafka Pipeline Applications](https://engineering.zalando.com/posts/2017/10/event-first-development---moving-towards-kafka-pipeline-applications.html) - `2017` - :books:
- [Reattaching Kafka EBS in AWS](https://engineering.zalando.com/posts/2017/10/reattaching-kafka-ebs-in-aws.html) - `2017` - :books:
- [Real-time Ranking with Apache Kafka’s Streams API](https://engineering.zalando.com/posts/2017/11/real-time-ranking-kafka.html) - `2017` - :books:
- [Running Kafka Streams applications in AWS](https://engineering.zalando.com/posts/2017/11/running-kafka-streams-applications-aws.html) - `2017` - :books:
- [A Recipe for Kafka Lag Monitoring](https://engineering.zalando.com/posts/2017/12/recipe-for-kafka-lag-monitoring.html) - `2017` - :books:
- [Surviving Data Loss](https://engineering.zalando.com/posts/2017/12/backing-up-kafka-zookeeper.html) - `2017` - :books:

## Zopa Bank

- [Highly Available Kafka Consumers and Kafka Streams on Kubernetes](https://www.confluent.io/events/kafka-summit-london-2023/highly-available-kafka-consumers-and-kafka-streams-on-kubernetes/) - `2023` - :studio_microphone:
