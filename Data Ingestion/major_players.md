# Data Ingestion

## Technology

- AirByte
- upsolver
- Flink
- Amazon Kinesis
- Confluent
- Cloud PubSub
- Materialize
- **Apache Kafka**
  - Apache Kafka is a distributed data store optimized for ingesting and processing streaming data in real-time.
  - Kafka provides three main functions to its users:
    - Publish and subscribe to streams of records
    - Effectively store streams of records in the order in which records were generated
    - Process streams of records in real time
  - Kafka is primarily used to build real-time streaming data pipelines and applications that adapt to the data streams.
  - It combines messaging, storage, and stream processing to allow storage and analysis of both historical and real-time data.  
  
- **Apache Nifi**
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
  
- SyncSort
- WaveFront
- Apache Storm
- Data Torrent
- Apache Samza
- Gobblin
- Apache Fume
- Apache Sqoop
