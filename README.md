# Awesome Modern Data Tools 📊🚀
Welcome to Awesome Data Tools! This curated list brings together powerful open-source tools, frameworks, and resources for data engineering and data science. It started with inspiration from [pracdata's awesome-open-source-data-engineering](https://github.com/pracdata/awesome-open-source-data-engineering?tab=readme-ov-file) list and has grown into a resource to organize and explore the ever-evolving landscape of data technology.

Whether you're working with data pipelines, warehousing, processing, or analytics, this list is updated with tools encountered daily, selected for their utility, innovation, and relevance. Feel free to fork, star, and contribute by submitting PRs with any useful tools you’d like to see added!
# STORAGE SYSTEMS
This category encompasses various database management systems and storage solutions designed for different use cases and data models.

## Relational DBMS
Description: Traditional relational database management systems that store data in tables with rows and columns.

| Project | Description |
|---------|-------------|
| PostgreSQL | Advanced object-relational database management system |
| MySQL | One of the most popular open Source Databases |
| MariaDB | A popular MySQL server fork |
| Supabase | An open source Firebase alternative |
| SQLite | Most popular embedded database engine |

## Distributed SQL DBMS
Description: Distributed SQL databases that provide horizontal scalability while maintaining SQL compatibility.

| Project | Description |
|---------|-------------|
| Citus | A popular distributed PostgreSQL as an extension |
| CockroachDB | A cloud-native distributed SQL database |
| YugabyteDB | A cloud-native distributed SQL database |
| TiDB | A cloud-native, distributed, MySQL-Compatible database |
| OceanBase | A scalable distributed relational database |
| ShardingSphere | A Distributed SQL transaction & query engine |
| Neon | A serverless open-source alternative to AWS Aurora Postgres |

## Cache Store
Description: High-performance in-memory data stores designed for caching.

| Project | Description |
|---------|-------------|
| Redis | A popular key-value based cache store |
| Memcached | A high performance multithreaded key-value cache store |
| Dragonfly | A modern cache store compatible with Redis and Memcached APIs |

## In-memory SQL Database
Description: SQL databases that primarily operate in memory for high performance.

| Project | Description |
|---------|-------------|
| Apache Ignite | A distributed, ACID-compliant in-memory DBMS |
| ReadySet | A MySQL and Postgres wire-compatible caching layer |
| VoltDB | A distributed, horizontally-scalable, ACID-compliant database |

## Document Store
Description: NoSQL databases optimized for storing and querying JSON-like documents.

| Project | Description |
|---------|-------------|
| MongoDB | A cross-platform, document-oriented NoSQL database |
| RavenDB | An ACID NoSQL document database |
| RethinkDB | A distributed document-oriented database for real-time applications |
| CouchDB | A Scalable document-oriented NoSQL database |
| Couchbase | A modern cloud-native NoSQL distributed database |
| FerretDB | A truly Open Source MongoDB alternative! |

## NoSQL Multi-model
Description: Databases supporting multiple data models like documents, graphs, and key-value pairs.

| Project | Description |
|---------|-------------|
| OrientDB | A Multi-model DBMS supporting Graph, Document, Reactive, Full-Text and Geospatial models |
| ArrangoDB | A Multi-model database with flexible data models for documents, graphs, and key-values |
| SurrealDB | A scalable, distributed, collaborative, document-graph database |
| EdgeDB | A graph-relational database with declarative schema |

## Graph Database
Description: Databases optimized for storing and querying graph-structured data.

| Project | Description |
|---------|-------------|
| Neo4j | A high performance leading graph database |
| JunasGraph | A highly scalable distributed graph database |
| HugeGraph | A fast-speed and highly-scalable graph database |
| NebulaGraph | A distributed, horizontal scalability, fast open-source graph database |
| Cayley | Inspired by the graph database behind Google's Knowledge Graph |
| Dgraph | A horizontally scalable and distributed GraphQL database with a graph backend |

## Distributed Key-value Store
Description: Scalable distributed systems for storing key-value pairs.

| Project | Description |
|---------|-------------|
| Riak | A decentralized key-value datastore from Basho Technologies |
| FoundationDB | A distributed, transactional key-value store from Apple |
| etcd | A distributed reliable key-value store written in Go |
| TiKV | A distributed transactional key-value database, originally created to complement TiDB |
| Immudb | A database with built-in cryptographic proof and verification |

## Wide-column Key-value Store
Description: Distributed databases optimized for storing and processing large-scale columnar data.

| Project | Description |
|---------|-------------|
| Apache Cassandra | A highly-scalable LSM-Tree based partitioned row store |
| Apache Hbase | A distributed wide column-oriented store modeled after Google' Bigtable |
| Scylla | LSM-Tree based wide-column API-compatible with Apache Cassandra and Amazon DynamoDB |
| Apache Accumulo | A distributed key-value store with scalable data storage and retrieval, on top of Hadoop |

## Embedded Key-value Store
Description: Lightweight key-value databases designed to be embedded within applications.

| Project | Description |
|---------|-------------|
| LevelDB | A fast key-value storage library written at Google |
| RocksDB | An embeddable, persistent key-value store developed by Meta (Facebook) |
| MyRocks | A RocksDB storage engine for MySQL |
| BadgerDB | An embeddable, fast key-value database written in pure Go |

## Search Engine
Description: Specialized databases optimized for full-text search and information retrieval.

| Project | Description |
|---------|-------------|
| Apache Solr | A fast distributed search database built on Apache Lucene |
| Elastic Search | A distributed, RESTful search engine optimized for speed |
| Sphinx | A fulltext search engine with high speed of indexation |
| Meilisearch | A fast search API with great integration support |
| OpenSearch | A community-driven, open source fork of Elasticsearch and Kibana |
| Quickwit | A fast cloud-native search engine for observability data |

## Streaming Database
Description: Databases designed for processing and analyzing real-time data streams.

| Project | Description |
|---------|-------------|
| RasingWave | A scalable Postgres for stream processing, analytics, and management |
| Materialize | A real-time data warehouse purpose-built for operational workloads |
| EventStoreDB | An event-native database designed for event sourcing and event-driven architectures |
| KsqlDB | A database for building stream processing applications on top of Apache Kafka |

## Time-Series Database
Description: Databases optimized for storing and querying time-series data.

| Project | Description |
|---------|-------------|
| Influxdb | A scalable datastore for metrics, events, and real-time analytics |
| TimeScaleDB | A fast ingest time-series SQL database packaged as a PostgreSQL extension |
| Apache IoTDB | An Internet of Things database with seamless integration with Hadoop and Spark ecology |
| Netflix Atlas | An n-memory dimensional time series database developed by Netflix |
| QuestDB | A time-series database for fast ingest and SQL queries |
| TDEngine | A high-performance, cloud native time-series database optimized for IoT |
| KairosDB | A scalable time series database written in Java |

## Columnar OLAP Database
Description: Databases optimized for analytical processing with columnar storage.

| Project | Description |
|---------|-------------|
| Apache Kudu | A column-oriented data store for the Apache Hadoop ecosystem |
| Greeenplum | A column-oriented massively parallel PostgreSQL for analytics |
| MonetDB | A high-performance columnar database originally developed by CWI |
| DuckDB | An in-process SQL OLAP Database Management System |
| Databend | An elastic, workload-aware cloud-native data warehouse built in Rust |
| ByConity | A cloud-native data warehouse forked from ClickHouse |
| hydra | A fast column-oriented Postgres extension |

## Real-time OLAP Engine
Description: Engines designed for real-time analytical processing.

| Project | Description |
|---------|-------------|
| ClickHouse | A real-time column-oriented database originally developed at Yandex |
| Apache Pinot | A real-time distributed OLAP datastore open sourced by LinkedIn |
| Apache Druid | A high performance real-time OLAP engine by Metamarkets |
| Apache Kylin | A distributed OLAP engine for multi-dimensional analysis on Hadoop |
| Apache Doris | A high-performance real-time analytical database based on MPP |
| StarRocks | A sub-second OLAP database supporting multi-dimensional analytics |

# DATA LAKE PLATFORM

## Distributed File System
Description: Scalable file systems for distributed storage environments.

| Project | Description |
|---------|-------------|
| Apache Hadoop HDFS | A highly scalable distributed block-based file system |
| GlusterFS | A scalable distributed storage that can scale to several petabytes |
| JuiceFS | A distributed POSIX file system built on top of Redis and S3 |
| Lustre | A distributed parallel file system with global POSIX-compliant namespace |

## Distributed Object Store
Description: Systems for storing and managing distributed object storage.

| Project | Description |
|---------|-------------|
| Apache Ozone | A scalable, redundant object store for Apache Hadoop |
| Ceph | A distributed object, block, and file storage platform |
| Minio | A high performance object storage API compatible with Amazon S3 |

## Serialisation Framework
Description: Frameworks for efficient data serialization and storage formats.

| Project | Description |
|---------|-------------|
| [Apache Parquet](https://parquet.apache.org/) | An efficient columnar binary storage format that supports nested data |
| Apache Avro | An efficient and fast row-based binary serialisation framework |
| Apache ORC | A self-describing type-aware columnar file format for Hadoop |
| [Lance By LanceDB](https://lancedb.github.io/lance/) | use cases’ are more targeted towards ML (multi modal). Claims 100x faster than Parquet. (check out [this blog post](https://blog.lancedb.com/lance-v2/)) |
| [Nimble](https://github.com/facebookincubator/nimble) | Nimble by Meta is a new columnar file format for large datasets. It is meant to be a replacement for file formats such as Parquet, ORC. Suited for ML use cases (feature store). |
| [Vortex](https://github.com/spiraldb/vortex) |  [Vortex](https://www.linkedin.com/posts/dipankar-mazumdar_parquet-bigdata-dataengineering-activity-7253095572268613632-Wk2r/) is another one that claims to provide faster random access reads (100-200x faster) and scans (2-10x faster), while preserving approximately the same compression ratio and write throughput as Parquet with ZSTD. (Vortex’s default compression strategy is based on the BtrBlocks paper) |

## Open Table Format
Description: Open-source table formats for data lake storage.

| Project | Description |
|---------|-------------|
| Apache Hudi | An open table format for incremental data ingestion on cloud and Hadoop |
| Apache Iceberg | A high-performance table format for large analytic tables by Netflix |
| Delta Lake | A storage framework for building Lakehouse architecture by Databricks |
| Apache Paimon | An Apache incubating project for streaming high-speed data ingestion |
| OneTable | A unified framework for interoperability across table formats |

# DATA INTEGRATION

## Data Integration Platform
Description: Platforms for building and managing data integration pipelines.

| Project | Description |
|---------|-------------|
| Airbyte | A data integration platform for ETL/ELT with wide range of connectors |
| Apache Nifi | A reliable, scalable low-code data integration platform |
| Apache Camel | An embeddable integration framework for enterprise patterns |
| Apache Gobblin | A distributed data integration framework by LinkedIn |
| Apache Inlong | An integration framework for massive data, built at Tencent |
| Meltano | A declarative code-first data integration engine |
| Apache SeaTunnel | A high-performance, distributed data integration tool |

## CDC Tool
Description: Tools for capturing and processing database changes.

| Project | Description |
|---------|-------------|
| Debezium | A change data capture framework supporting variety of databases |
| Kafka Connect | A streaming data integration framework on top of Apache Kafka |
| Flink CDC Connectors | CDC Connectors for Apache Flink engine |
| Brooklin | A platform for streaming data between heterogeneous systems |
| RudderStack | A headless Customer Data Platform, alternative to Segment |

## Log & Event Collection
Description: Tools for collecting and processing logs and events.

| Project | Description |
|---------|-------------|
| CloudQuery | An ETL tool for syncing data from cloud APIs to destinations |
| Snowplow | A cloud-native engine for collecting behavioral data |
| EventMesh | A serverless event middleware for event data collection |
| Apache Flume | A scalable distributed log aggregation service |
| Steampipe | A zero-ETL solution for getting data from APIs and services |

## Event Hub
Description: Platforms for managing distributed messaging and event streaming.

| Project | Description |
|---------|-------------|
| Apache Kafka | A highly scalable distributed event store and streaming platform |
| NSQ | A realtime distributed messaging platform for scale |
| Apache Pulsar | A scalable distributed pub-sub messaging system |
| Apache RocketMQ | A cloud native messaging and streaming platform |
| Redpanda | A high performance Kafka API compatible streaming platform |
| Memphis | A scalable platform for building event-driven applications |

# DATA PROCESSING AND COMPUTATION

## Unified Processing
Description: Frameworks that support both batch and stream processing.

| Project | Description |
|---------|-------------|
| Apache Beam | A unified model supporting execution on distributed processing backends |
| Apache Spark | A unified analytics engine for large-scale data processing |
| Dinky | A unified streaming & batch platform based on Apache Flink |

## Batch Processing
Description: Frameworks specifically designed for processing large batches of data.

| Project | Description |
|---------|-------------|
| Hadoop MapReduce | A highly scalable distributed batch processing framework |
| Apache Tez | A distributed data processing pipeline for Apache Hive and Hadoop |

## Stream Processing
Description: Frameworks for processing real-time data streams.

| Project | Description |
|---------|-------------|
| Apache Flink | A scalable high throughput stream processing framework |
| Apache Samza | A distributed stream processing framework using Kafka and Hadoop |
| Apache Storm | A distributed realtime computation system based on Actor Model |
| Benthos | A high performance declarative stream processing engine |
| Akka | A highly concurrent, distributed, message-driven processing system |
| Bytewax | A Python stream processing framework with Rust engine |

## Parallel Python Execution
Description: Tools for parallel and distributed Python computation.

| Project | Description |
|---------|-------------|
| Vaex | A high performance Python library for big tabular datasets |
| Dask | A flexible parallel computing library for analytics |
| Polars | A multithreaded Dataframe with vectorized query engine in Rust |
| PySpark | An interface for Apache Spark in Python |
| RAY | A unified framework for scaling python applications |
| Apache Arrow | An efficient in-memory data format |

# WORKFLOW MANAGEMENT & DATAOPS

## Workflow Orchestration
Description: Tools for managing and scheduling data workflows and pipelines.

| Project | Description |
|---------|-------------|
| Apache Airflow | A platform for creating and scheduling DAGs of tasks |
| Prefect | A Python based workflow orchestration tool |
| Argo | A container-native workflow engine for Kubernetes |
| Azkaban | A batch workflow job scheduler for Hadoop jobs |
| Cadence | A distributed, scalable orchestration platform |
| Dagster | A cloud-native data pipeline orchestrator in Python |
| Apache DolphinScheduler | A low-code workflow orchestration platform |
| Luigi | A python library for building complex pipelines |
| Flyte | A scalable workflow platform for data and ML workloads |
| Kestra | A declarative workflow orchestration platform |
| Mage.ai | A platform for managing data pipelines |
| Temporal | A resilient workflow management system from Uber's Cadence |
| Windmill | A fast workflow engine, alternative to Airplane and Retool |
| [Hamilton](https://github.com/DAGWorks-Inc/hamilton) | Hamilton helps data scientists and engineers define testable, modular, self-documenting dataflows, that encode lineage/tracing and metadata. Runs and scales everywhere python does.|

## Data Quality
Description: Tools for ensuring and validating data quality.

| Project | Description |
|---------|-------------|
| Data-diff | A tool for comparing tables within or across databases |
| Great Expectations | A data validation and profiling tool in Python |

## Data Versioning
Description: Tools for version control of data assets.

| Project | Description |
|---------|-------------|
| LakeFS | A data version control for data stored in data lakes |
| Project Nessie | A transactional Catalog for Data Lakes with Git-like semantics |

## Data Modeling
Description: Tools for transforming and modeling data.

| Project | Description |
|---------|-------------|
| dbt | A data modeling and transformation tool for pipelines |
| SQLMesh | A data transformation framework compatible with dbt |

# DATA INFRASTRUCTURE

## Resource Scheduling
Description: Tools for managing and scheduling compute resources.

| Project | Description |
|---------|-------------|
| Apache Yarn | The default Resource Scheduler for Apache Hadoop clusters |
| Apache Mesos | A resource scheduling and cluster abstraction framework |
| Kubernetes | A production-grade container scheduling tool |
| Docker | The popular OS-level virtualization software |

# DATA INFRASTRUCTURE (continued)

## Cluster Administration
Description: Tools for managing and monitoring distributed clusters.

| Project | Description |
|---------|-------------|
| Apache Ambari | A tool for provisioning and managing Hadoop clusters |
| Apache Helix | A generic cluster management framework by LinkedIn |

## Security
Description: Tools for managing security and access control.

| Project | Description |
|---------|-------------|
| Apache Knox | A gateway and SSO service for Hadoop clusters |
| Apache Ranger | A security and governance platform for Hadoop |
| Kerberos | A popular enterprise network authentication protocol |

## Metrics Store
Description: Systems for storing and managing metrics data.

| Project | Description |
|---------|-------------|
| Influxdb | A scalable datastore for metrics and events |
| Mimir | A scalable long-term metrics storage for Prometheus |
| OpenTSDB | A distributed Time Series Database on Apache Hbase |
| M3 | A distributed TSDB and metrics storage aggregator |

## Observability Framework
Description: Frameworks for monitoring and observing system behavior.

| Project | Description |
|---------|-------------|
| Prometheus | A popular metric collection and management tool |
| ELK | A observability stack with Elasticsearch, Kibana, Beats, Logstash |
| Graphite | An established infrastructure monitoring system |
| OpenTelemetry | APIs, SDKs, and tools for managing and monitoring metrics |
| VictoriaMetrics | A scalable monitoring solution with time series database |
| Zabbix | A real-time infrastructure and application monitoring service |

## Monitoring Dashboard
Description: Tools for visualizing monitoring data.

| Project | Description |
|---------|-------------|
| Grafana | A popular observability and data visualization platform |
| Kibana | The visualization dashboard for Elasticsearch |
| RConsole | A UI for monitoring Apache Kafka and Redpanda workloads |

## Log & Metrics Pipeline
Description: Tools for collecting and processing logs and metrics.

| Project | Description |
|---------|-------------|
| Fluentd | A metric collection, buffering and router service |
| Fluent Bit | A fast log processor from the Fluentd ecosystem |
| Logstash | A server-side log processor, part of the ELK stack |
| Telegraf | A plugin-driven server agent for collecting metrics |
| Vector | A high-performance observability data pipeline |
| StatsD | A network daemon for metrics collection and routing |

# METADATA MANAGEMENT

## Metadata Platform
Description: Platforms for managing and organizing metadata across data systems.

| Project | Description |
|---------|-------------|
| Amundsen | A data discovery and metadata engine by Lyft |
| Apache Atlas | A data observability platform for Hadoop ecosystem |
| DataHub | A metadata platform for modern data stack by Netflix |
| Marquez | A metadata service for collection and visualization |
| ckan | A data management system for cataloging data |
| Open Metadata | A unified platform for discovery and governance |

## Open Standards
Description: Standards and frameworks for metadata management.

| Project | Description |
|---------|-------------|
| Open Lineage | An open standard for lineage metadata collection |
| Open Metadata | A unified metadata platform providing open standards |
| Egeria | Open metadata and governance standards |

## Schema Service
Description: Services for managing schema definitions.

| Project | Description |
|---------|-------------|
| Hive Metastore | A schema management service from Apache Hive |
| Confluent Schema Registry | A schema registry for Kafka by Confluent |

# ANALYTICS & VISUALISATION

## BI & Dashboard
Description: Tools for business intelligence and data visualization.

| Project | Description |
|---------|-------------|
| Apache Superset | A popular data visualization and exploration platform |
| Metabase | A simple data visualization and exploration dashboard |
| Redash | A tool to explore, query, and visualize data |
| Streamlit | A python tool to package data as web apps |

## Query & Collaboration
Description: Tools for querying data and collaborative analysis.

| Project | Description |
|---------|-------------|
| Hue | A query tool with Hadoop support, by Cloudera |
| Apache Zeppelin | A web-based Notebook for interactive analytics |
| Querybook | A simple query and notebook UI by Pinterest |
| Jupyter | A popular interactive web-based notebook application |

## MPP Query Engine
Description: Massively Parallel Processing engines for distributed querying.

| Project | Description |
|---------|-------------|
| Apache Hive | A data warehousing and MPP engine on Hadoop |
| Apache Implala | A MPP engine for Hadoop clusters by Cloudera |
| Presto | A distributed SQL query engine for big data |
| Trino | The former PrestoSQL distributed SQL query engine |
| Apache Drill | A distributed MPP query engine for NoSQL and Hadoop |

# ANALYTICS & VISUALISATION (continued)

## Semantic Layer
Description: Tools for creating and managing semantic data models.

| Project | Description |
|---------|-------------|
| Alluxio | A data orchestration and virtual distributed storage system |
| Cube | A semantic layer for building data applications |
| Apache Linkis | A computation middleware for applications and data engines |

# ML/AI PLATFORM

## Vector Storage
Description: Databases optimized for storing and querying vector embeddings.

| Project | Description |
|---------|-------------|
| milvus | A cloud-native vector database for AI applications |
| qdrant | A high-performance, scalable Vector database for AI |
| chroma | An AI-native embedding database for LLM apps |
| marqo | An end-to-end vector search engine for text and images |
| LanceDB | A serverless vector database written in Rust |
| weaviate | A scalable database supporting objects and vectors |
| deeplake | A storage format optimized for deep-learning applications |
| Vespa | A storage for vectors, tensors, text and structured data |
| vald | A scalable distributed vector search engine |
| pgvector | A vector similarity search Postgres extension |

## MLOps
Description: Tools and platforms for managing machine learning operations.

| Project | Description |
|---------|-------------|
| mlflow | A platform for ML development and lifecycle management |
| Metaflow | A tool for ML/AI and data science projects by Netflix |
| SkyPilot | A framework for running LLMs and AI on any cloud |
| Jina | A tool to build multimodal AI with cloud-native stack |
| NNI | An autoML toolkit from Microsoft |
| BentoML | A framework for building reliable AI applications |
| Determined AI | An ML platform for distributed training and tuning |
| RAY | A unified framework for scaling AI and Python applications |
| kubeflow | A cloud-native platform for ML operations |




