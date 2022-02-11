# Data Ingestion

## Technology

- **AirByte** [https://airbyte.com/]
  - Airbyte is the new open-source data integration platform that syncs data from applications, APIs & databases to data warehouses, lakes and other destinations.
  - Some of the features provided are Built for extensibility, Optional normalized schemas, Full-grade scheduler, Real-time monitoring, Incremental updates, Debugging autonomy.
  - Services like optional, normalized schema let engineers opt for raw data to get going with their own normalization activities.
  - Also, analysts can start using the data right away by opting for a similar module. Integrated APIs deployed by the software lets users get customized notifications without unnecessary delays.
  - Companies just need to authenticate their warehouses and sources to get access to connectors that are capable of adapting to API related changes and schemas.

- **upsolver** [https://www.upsolver.com/]
  - Upsolver is the only SQL pipeline platform for cloud data lakes. It empowers any data practitioner to design pipelines that deliver continuous analytics-ready data in days, not the months required when hand-coding and orchestrating Spark.
  - Features given are:
    - Reading Data - Upsolver reads your raw data as is: JSON, CSV, TSV, Avro, Parquet and more.
      - Build-it integrations: S3 / Kafka / Kinesis
      - Exactly-once read from Kafka / Kinesis
      - Replay from S3
    - Delivering data - Upsolver delivers data to:
      - S3 in various file formats including JSON, CSV, AVRO, Parquet. Upsolver also manages partitions and optimizes S3 file sizes.
      - Analytics databases like Athena, Redshift and ElasticSearch.
      - Upsolver itself for key based API requests in under 1 millisecond.
    - Enrichments - Upsolver offers 100s of functions to clean and enrich raw data including hierarchies and arrays:
      - Standard ansi-SQL functions
      - Advanced functions for numbers, strings, dates and arrays
      - Extraction of geo data from IPs (using MaxMind)
      - User agent parser, Filters and User defined functions in Python
    - Aggregations - Upsolver offers streaming aggregations that work for any size time window (using S3):
      - Regular or aggregated output tables
      - Sessionization
      - Accurate count distinct in real-time and at scale
      - Nested aggregations for user/device profiling
    - Monitoring - All of Upsolver’s monitoring metrics are sent to internal monitoring system like DataDog or Influx. Upsolver user interface can also be used for monitoring.
    - Deployment - Upsolver can be deployed either on our VPC or your VPC.
    - Data Privacy - Your data always remains private – it resides ONLY on your S3.

- **Flink** [https://flink.apache.org/]
  - Apache Flink is an open-source, unified stream-processing and batch-processing framework developed by the Apache Software Foundation. The core of Apache Flink is a distributed streaming data-flow engine written in Java and Scala. It executes arbitrary dataflow programs in a data-parallel and pipelined manner. Flink's pipelined runtime system enables the execution of bulk/batch and stream processing programs.
  - Flink’s features include support for stream and batch processing, sophisticated state management, event-time processing semantics, and exactly-once consistency guarantees for state.
  - Moreover, Flink can be deployed on various resource providers such as YARN, Apache Mesos, and Kubernetes but also as stand-alone cluster on bare-metal hardware.
  - Configured for high availability, Flink does not have a single point of failure. Flink has been proven to scale to thousands of cores and terabytes of application state, delivers high throughput and low latency, and powers some of the world’s most demanding stream processing applications.

- **Amazon Kinesis**[https://aws.amazon.com/kinesis/]
  - Amazon Kinesis makes it easy to collect, process, and analyze real-time, streaming data so you can get timely insights and react quickly to new information.
  - Offers key capabilities to cost-effectively process streaming data at any scale, along with the flexibility to choose the tools that best suit the requirements of your application. With Amazon Kinesis, you can ingest real-time data such as video, audio, application logs, website clickstreams, and IoT telemetry data for machine learning, analytics, and other applications.
  - Enables you to process and analyze data as it arrives and respond instantly instead of having to wait until all your data is collected before the processing can begin.
  - Use Cases of Amazon Kinesis are:
    - Data log and data feed intake − We need not wait to batch up the data, we can push data to an Amazon Kinesis stream as soon as the data is produced. It also protects data loss in case of data producer fails. For example: System and application logs can be continuously added to a stream and can be available in seconds when required.
    - Real-time graphs − We can extract graphs/metrics using Amazon Kinesis stream to create report results. We need not wait for data batches.
    - Real-time data analytics − We can run real-time streaming data analytics by using Amazon Kinesis.
  - Key Features include:
    - Ease of Use: Users can seamlessly set up custom streams and deploy their data pipelines by setting the requirements and start streaming quickly.
    - No Server Administration Required: There is no infrastructure that is required to be managed and many of the services are operated automatically so no continuous administration for deployments is required.
    - Stream from Millions of Devices: The SDKs [Software Development Kit] provided with Amazon Video Streams enable streaming media to AWS for playback, storage, analytics, machine learning and other relevant processes.
    - Cost Efficient: The platform offers pay as you use model which makes it cost-effective for organizations.
    - High Scalability: Based on Amazon Web Services, it provides the ability to rapidly scale up and down according to the requirements of the user.

- **Confluent** [https://www.confluent.io/]
  - Confluent is pioneering a fundamentally new category of data infrastructure focused on data in motion. Our cloud-native offering is the foundational platform for data in motion is designed to be the intelligent connective tissue enabling real-time data, from multiple sources, to constantly stream across the organization.
  - Built as a cloud-native service, Confluent Cloud offers a serverless experience with self-serve provisioning, elastic scaling, and usage-based billing so that you pay for what you stream and not for provisioned infrastructure.
  - Confluent Cloud protects your data using industry-standard security features, and the service reliability is backed by an enterprise-grade uptime SLA.
  - In addition to fully managing your Kafka clusters, Confluent Cloud also has fully managed components including Schema Registry, connectors to popular cloud services such as Amazon S3 and Redshift, and ksqlDB, enabling you to harness the full power of real-time events without any of the operational burden.
  - Offers a streaming platform based on Apache Kafka that enables companies to easily access data as real-time streams. The company's platform offers an open-source technology that acts as a real-time, fault-tolerant and highly scalable messaging system, enabling companies to move data from isolated systems into a real-time datapipeline where they can act on it immediately.
  - Few of the use cases of using Confluent are Customer 360, Fraud Detection, Microservices, Hybrid and Multicloud.
  
- **Cloud PubSub**

- **Materialize** [https://materialize.com/]
  - Materialize is a streaming database for real-time applications. Materialize accepts input data from a variety of streaming sources (like Kafka), data stores and databases (like S3 and Postgres), and files (like CSV and JSON), and lets you query them using SQL.
  - It is also a reactive database that delivers incremental view updates. We help developers easily build with streaming data using standard SQL.
  - Helps to Connect Your Data Sources, Create Real-Time Materialized Views, Build Live Dashboards and Experiences.
  - Some of the use cases of this are Real-Time Alerts and Notifications, Fraud Detection and Risk Management, Logistics and IoT Management, Event-Driven Features, Personalized Customer Experiences and Predictive Machine Learning.
  - Features are:
    - Materialize instead keeps the results of the queries and incrementally updates them as new data comes in.Your database often acts as if it’s never been asked that question before, which means it can take a long time to come up with an answer, each and every time you pose the query. So, rather than recalculating the answer each time it’s asked, Materialize continually updates the answer and gives you the answer’s current state from memory.
    - Materialize supports incrementally updating a much broader set of views than is common in traditional databases (e.g. views over multi-way joins with complex aggregations), and can do incremental updates in the presence of arbitrary inserts, updates, and deletes in the input streams.
    - If you perform any OLAP queries over relational data and want to reduce the time it takes to refresh answers to common queries, Materialize can make that happen.
    - For a sense of scale, it can take queries that most teams would run once-per-day and instead provide sub-second or single-digit second answers.

- **Apache Kafka** [https://kafka.apache.org/]
  - Apache Kafka is a distributed data store optimized for ingesting and processing streaming data in real-time.
  - Kafka provides three main functions to its users:
    - Publish and subscribe to streams of records
    - Effectively store streams of records in the order in which records were generated
    - Process streams of records in real time
  - Kafka is primarily used to build real-time streaming data pipelines and applications that adapt to the data streams.
  - It combines messaging, storage, and stream processing to allow storage and analysis of both historical and real-time data.  
  
- **Apache Nifi** [https://nifi.apache.org/]
  - Designed to automate the flow of data between software systems .
  - Apache NiFi supports powerful and scalable directed graphs of data routing, transformation, and system mediation logic.
  - Web-based user interface
    - Seamless experience between design, control, feedback, and monitoring
  - Highly configurable
    - Loss tolerant vs guaranteed delivery
    - Low latency vs high throughput
    - Dynamic prioritization
    - Flow can be modified at runtime
    - Back pressure
  - Data Provenance
    - Track dataflow from beginning to end
    - NiFi automatically records, indexes, and makes available provenance data as objects flow through the system even across fan-in, fan-out, transformations, and more. This information becomes extremely critical in supporting compliance, troubleshooting, optimization, and other scenarios.
  - Designed for extension
    - Build your own processors and more
    - Enables rapid development and effective testing
  - Secure
    - SSL, SSH, HTTPS, encrypted content, etc...
      - A dataflow is only as good as it is secure. NiFi at every point in a dataflow offers secure exchange through the use of protocols with encryption such as 2-way SSL. In addition NiFi enables the flow to encrypt and decrypt content and use shared-keys or other mechanisms on either side of the sender/recipient equation.
    - Multi-tenant authorization and internal authorization/policy management.
      - The authority level of a given dataflow applies to each component, allowing the admin user to have fine grained level of access control. This means each NiFi cluster is capable of handling the requirements of one or more organizations. Compared to isolated topologies, multi-tenant authorization enables a self-service model for dataflow management, allowing each team or organization to manage flows with a full awareness of the rest of the flow, to which they do not have access.
  
- **SyncSort**[https://www.precisely.com/]
  - Syncsort now also known as Pricesely is the global leader in Big Iron to Big Data software. Organizes data everywhere, to keep the world working – the same data that powers machine learning, AI and predictive analytics.
  - Their Products provide a simple way to optimize, assure, integrate, and advance data, helping to solve for the present and prepare for the future.
  - Syncsort software provides specialized solutions spanning “Big Iron to Big Data,” including next gen analytical platforms such as Hadoop, cloud, and Splunk.
  - Connect helps you take control of your data from mainframe to cloud. Integrate data through batch and real-time ingestion for advanced analytics, comprehensive machine learning and seamless data migration.
  - Connect leverages the expertise Precisely has built over decades as a leader in mainframe sort and IBM i data availability and security to lead the industry in accessing and integrating complex data. Access to all your enterprise data for the most critical business projects is ensured by support for a wide range of sources and targets for all your ELT and CDC needs.

- **WaveFront** [https://docs.wavefront.com/index.html]
  - Wavefront is a high-performance streaming analytics platform that supports observability for metrics, counters, histograms, and traces/spans. Wavefront is unique because it scales to very high data ingestion rates and query loads. You can collect data from many services and sources across your entire application stack, and can look at details for earlier data that were ingested earlier.
  - It is a SaaS-based, enterprise observability platform with the ability to visualize, alert and query data.
  - Can use Wavefront to ingest time-series metrics, histograms, traces and spans logs. Data can be sent into Wavefront through integrations, a Wavefront proxy, or through direct ingestion.
  - Wavefront Top is an open source tool to easily visualize the overall data ingestion shape into your Wavefront instance and quickly identify namespaces or sources with high points per second (PPS) and high lag time.
  - Wavefront Top improves monitoring across your organization, allowing you to quickly discover which namespaces are sending a lot of data, calculate the percentage of “accessed” data, and view the range of values of namespaces.
  - The advantage of using the proxy benefits from Wavefront are:
    - Prevent data loss, optimize network bandwidth – The proxy buffers and manages data traffic. Even if there’s a connectivity problem, you don’t lose data points.
    - Simple firewall configuration – The proxy receives metrics from many agents on different hosts and forwards those metrics to the Wavefront service. You don’t need to open internet access for each of the agents.
    - Enrich or filter data – You can set up the proxy preprocessor to filter data before it’s sent to Wavefront.
    - Examine bottlenecks – Each proxy generates its own metrics. You can learn about incoming and outgoing data in the Wavefront Service and Proxy dashboard of the Wavefront Usage integration.

- Apache Storm
- Data Torrent
- Apache Samza
- Gobblin
- Apache Fume
- Apache Sqoop
