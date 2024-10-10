# Hi!

* Matteo Francia, Ph.D.
  * Email: [m.francia@unibo.it](mailto:m.francia@unibo.it)
  * Assistant Professor (junior) @ DISI, UniBO
  * www: [https://www.unibo.it/sitoweb/m.francia/en](https://www.unibo.it/sitoweb/m.francia/en)
* Research topics
  * Big data / database
  * Precision agriculture and spatio-temporal analytics
* BIG (Business Intelligence Group)
  * [https://big.csr.unibo.it/](https://big.csr.unibo.it/teaching/)

# Table of Contents and Exam

* Handling data pipelines in the Cloud
  * Introduction to __data platforms__: shifting from databases to well-integrated data ecosystems
  * Definition of __cloud computing__ and taxonomy of cloud services
  * Introduction to the most __relevant cloud platforms__
  * Introduction to the __billing models__ of cloud computing services
  * Cluster __migration__: on-premises vs on-cloud
  * Real __case studies + labs__
* Seminars by companies working with cloud and big data platforms
* Connect the dots
  * Information systems, BI, data mining, big data, and machine learning
* ... __all these points__ will be part of the oral examination!:)

# Table of Contents and Exam

* Questions on all (__theoretical__ and __practical__) aspects of the course
  * A __single session __ with both teachers
  * Exam covers __both modules__
  * __Seminars and labs__ are included
  * __Interaction during the lectures/labs __ is considered in the final evaluation
* No scheduled dates, just come __when you are ready__
  * Send an email to [enrico.gallinucci@unibo.it](mailto:enrico.gallinucci@unibo.it) to book an appointment
  * At least one week in advance
* According to the University's regulation
  * Exams must be in presence
  * __Cannot refuse a grade more than once__
* Be prepared: you have to wait __1 month before trying again__ (in any case)

# So far

> Digital transformation
>
> The process of using digital technologies to create new — or modify existing — business processes, culture, and customer experiences to meet changing business and market requirements


* You have acquainted/practiced with __on-premises__ solutions
  * You were given a working hardware cluster
  * ... to deploy software applications on Hadoop-based stack
* In the perspective of digital transformation, let us guess
  * How would you start from scratch?
  * How much time would it take?

# So far

* No easy answers
* Big-data (distributed) architectures require a lot of skills
  * __Configuration__: how do I set up dozens of new machines?
  * __Networking__: how do I cable dozens of machines?
  * __Management__: how do I replace a broken disk?
  * __Upgrade__: how do I extend the cluster with new services/machines?
  * (energy and cooling, software licenses, insurance...)

[https://aws.amazon.com/compliance/data-center/data-centers/](https://aws.amazon.com/compliance/data-center/data-centers/)

# So far

* Two sides of the same coin, and your profile is a perfect? fit
  * Technological perspective
    * How do we configure a distributed environment?
    * How do we set up/integrate/control independent services?
    * How do we orchestrate data flows?
  * Business perspective
    * Can we afford to spend resources on tasks that are not mission oriented?
    * No free lunch, each choice has cost/benefit
    * How much time does it take to master a technology?
    * How many people do I need?
* ... but first, which are our **data needs**?

* Can we afford to spend resources on tasks that are not mission oriented?
  * Mission: a statement used by a company to explain its purpose(s)

# Teaching material

:::: {.columns}
::: {.column width=25%}

![](imgs/slides0.png)

:::
::: {.column width=25%}

![](imgs/slides1.jpg)

:::
::: {.column width=25%}

![](imgs/slides2.jpg)

:::
::: {.column width=25%}

![](imgs/slides5.png)

:::
::: {.column width=33%}

![](imgs/slides3.png)

:::
::: {.column width=33%}

![](imgs/slides4.png)

:::
::::

# Teaching material

* You will find all you need in these slides
* However, keeping up the pace with data platforms and cloud is hard
  * There is a rapid development of technologies, and not all of them will survive
  * Books are easily outdated with respect to cutting-edge services and technologies
  * Research papers (often) describe solutions that are not commercial yet
  * (IRL) You will need to deal with a lot of (bad) documentation, online articles, etc.
* Rule of thumb
  * Understand the general concepts
  * Do not be afraid of change
  * Connect the dots... and ask questions!

# -- newsection --

# From databases to data platforms

# How did we get here?

* __Data-Driven Innovation__
  * Use of data and _analytics_ to foster new products, processes and markets
  * Drive discovery and execution of innovation, achieving new services with a business value
* __Analytics__
  * A catch-all term for different business intelligence (BI)- and application-related initiatives
    * E.g., of analyzing information from a particular domain
    * E.g., applying BI capabilities to a specific content area (e.g., sales, service, supply chain)
* __Advanced Analytics__
  * (Semi-)Autonomous examination of data to discover deeper insights, make predictions, or generate recommendations (e.g., through data/text mining and machine learning)
* __Augmented Analytics__
  * Use of technologies such as machine learning and AI to assist with data preparation, insight generation and insight explanation to augment how people explore and analyze data

[https://www.gartner.com/en/information-technology/glossary](https://www.gartner.com/en/information-technology/glossary) (accessed 2022-08-01)

# How did we get here?

![](imgs/slides6.png)

# Data platform

* Companies are collecting tons of data to enable advanced analytics
  * Raw data is difficult to obtain, interpret, and maintain
  * Data is more and more heterogeneous
  * There is need for curating data to make it _consumable_
* Where are we _collecting/processing_ data?
  * Getting _value_ from data _is not_ (only) a matter of _storage_
  * Need integrated and multilevel analytical skills and techniques

* Getting _value_ from data _is not_ (only) a matter of _storage_
  * Any example?

> “It is a capital mistake to theorize before one has data. Insensibly, one begins to twist the facts to suit theories, instead of theories to suit facts.”
>
> – Sherlock Holmes

# Case study: photo gallery

:::: {.columns}
::: {.column width=50%}

![](imgs/slides7.png)

:::
::: {.column width=50%}

![](imgs/slides8.png)

:::
::::

# Data platform

:::: {.columns}
::: {.column width=50%}

> Database
>
> "A database is a _structured and persistent collection_ of information about some aspect of the real world organized and stored in a way that facilitates efficient retrieval and modification. The structure of a database is determined by an _abstract data model_. Primarily, it is this structure that differentiates a database from a data file."

:::
::: {.column width=50%}

![](imgs/20.svg)

:::
::::

Özsu M.T. (2018) Database. In: Encyclopedia of Database Systems. Springer, New York, NY. [https://doi.org/10.1007/978-1-4614-8265-9_80734](https://doi.org/10.1007/978-1-4614-8265-9_80734)

# Data platform

:::: {.columns}
::: {.column width=50%}

> Data Warehouse
>
> "A collection of data that supports decision-making processes. It provides the following features: subject-oriented, integrated and consistent, not volatile."

:::
::: {.column width=50%}

![](imgs/21.svg)

:::
::::

Matteo Golfarelli and Stefano Rizzi.  _Data warehouse design: Modern principles and methodologies_ . McGraw-Hill, Inc., 2009.

# OLTP vs OLAP?

# Data platform: OLTP vs OLAP

| Characteristic | OLTP | OLAP |
|:-: |:-: |:-: |
| Nature | Constant transactions (queries/updates) | Periodic large updates, complex queries |
| Examples | Accounting database, online retail transactions | Reporting, decision support |
| Type | Operational data | Consolidated data |
| Data retention | Short-term (2-6 months) | Long-term (2-5 years) |
| Storage | Gigabytes (GB) | Terabytes (TB) / Petabytes (PB) |
| Users | Many | Few |
| Protection | Robust, constant data protection and fault tolerance | Periodic protection |

# Data platform

:::: {.columns}
::: {.column width=50%}

> Schemaless databases
>
> There is no predefined schema the data must conform to before it's added to the database.
> As a result, you don't need to know the structure of your data, enabling you to store all your data more easily and quickly.

:::
::: {.column width=50%}

![](imgs/24.svg)

:::
::::

# Data platform

:::: {.columns}
::: {.column width=50%}

> Data lake
>
> “A DL is a _central repository_ system for _storage, processing, and analysis of raw data_, in which the data is kept in its _original format and is processed to be queried only when needed_. It can _store a varied amount of formats_ in big data ecosystems, from unstructured, semi-structured, to structured data sources”

:::
::: {.column width=50%}

![](imgs/slides9.jpg)

:::
::::

Couto, Julia, et al. "A Mapping Study about Data Lakes: An Improved Definition and Possible Architectures."  _SEKE_ . 2019.

[https://dunnsolutions.com/business-analytics/big-data-analytics/data-lake-consulting](https://dunnsolutions.com/business-analytics/big-data-analytics/data-lake-consulting)

# Data platform

![](imgs/26.svg)

# DWH vs Data Lake?

# Data platform: DWH vs Data Lake

| Characteristics | Data warehouse | Data lake |
|:-: |:-: |:-: |
| Data | Relational | Non-relational and relational |
| Schema | Designed prior to implementation (schema-on-write) | Written at the time of analysis (schema-on-read) |
| Price/performance | Fastest query results using higher cost storage | Query results getting faster using low-cost storage |
| Data quality | Highly curated data that serves as the central version of the truth | Any data, which may or may not be curated (e.g., raw data) |
| Users | Business analysts | Data scientists, data developers, and business analysts (using curated data) |
| Analytics | Batch reporting, BI, and visualizations | Machine learning, predictive analytics, data discovery, and profiling. |

# Data platform

* Data lakes have increasingly taken the role of data hubs
  * Eliminate up-front costs of ingestion and ETL since data are stored in original format
  * Once in DL, data are available for analysis by everyone in the organization
* Drawing a sharp line been storage/computation/analysis is hard
  * Is a database just storage?
  * What about SQL/OLAP?
* Blurring of the architectural borderlines
  * DL is often replaced by “data platform” or “data ecosystem”
  * Encompass systems supporting data-intensive storage, computation, analysis

# Data platform

* A data platform is a __centralized__ infrastructure that facilitates the ingestion, storage, management, and exploitation of large volumes of heterogeneous data. It provides a collection of __independent__ and __well-integrated__ services meeting __end-to-end__ data needs.
  * __Centralized__: is conceptually a single and unified component
  * __Independent__: a service is not coupled with any other
  * __Well-integrated__: services have interfaces that enable easy and frictionless composition
  * __End-to-end__: services cover the entire data life cycle
* Rationale: relieve users from complexity of administration and provision
  * Not only technological skills, but also privacy, access control, etc.
  * Users should only focus on functional aspects

# Data platform

* Are we done? No!
  * Lacking smart support to govern the complexity of data and transformations
  * Data transformations must be governed to prevent DP turning into a swamp
    * Amplified in data science, with data scientists prevailing data architects
    * Leverage descriptive metadata and maintenance to keep control over data

# Which functionalities for (automated) data management can you think about?

# Managing data platforms

  * Data provenance
  * Compression
  * Data profiling
  * Entity resolution
  * Data versioning
  * ...

# Data provenance

* Provenance (also referred to as lineage, pedigree, parentage, genealogy)
  * The description of the origins of data and the process by which it arrived at the database
  * Not only data products (e.g., tables, files), but also the processes that created them
* Examples of use cases
  * Business domain.  _Users traditionally work with an _ _organized data schema_ _, where the structure and _ _semantics of the data in use is shared_ _ across the corporation or even B2B. Yet, a large proportion of businesses deal with __bad quality data__. __Sources__ of bad data __need to be identified __and corrected to avoid costly errors in business forecasting._
  * Scientific/research domain. _Data_ used in the scientific field can be _ad hoc_ and driven by _individual researchers _or small communities. The scientific field is moving _towards more collaborative research_ and organizational boundaries are disappearing. _Sharing data and metadata across organizations is essential_, leading to a convergence on common schemes to ensure compatibility. Issues of _trust_, _quality_, and _copyright_ of data are significant when using third-party data in such a loosely connected network._

Simmhan, Yogesh L., Beth Plale, and Dennis Gannon. "A survey of data provenance techniques."  _Computer Science Department, Indiana University, Bloomington IN_ 47405 (2005): 69.

# Data provenance

* Astronomers are creating an international Virtual Observatory
  * A _federation_ of all the world significant astronomical _data resources_ coupled with _provision of the computational resources _ needed to exploit the data scientifically
  * Astronomy changed from being an individualistic to a _collective enterprise_
  * Telescope time is devoted/allocated to systematic sky surveys and analysis is performed using data from the archives
  * Astronomers are _increasingly relying on data that they did not take themselves_
  * Raw data bear _many instrumental signatures that must be removed _ in the process of generating data products

![](imgs/slides14.jpg)

Mann, Bob. "Some data derivation and provenance issues in astronomy."  _Workshop on Data Derivation and Provenance, Chicago_ . 2002.

[https://www.esa.int/Science_Exploration/Space_Science/Webb/Webb_inspects_the_heart_of_the_Phantom_Galaxy](https://www.esa.int/Science_Exploration/Space_Science/Webb/Webb_inspects_the_heart_of_the_Phantom_Galaxy) (accessed 2022-08-01)

# Data provenance

![](imgs/slides15.png)

Simmhan, Yogesh L., Beth Plale, and Dennis Gannon. "A survey of data provenance techniques."  _Computer Science Department, Indiana University, Bloomington IN_ 47405 (2005): 69.

# Data provenance

* Granularity
  * _Fine-grained_ (instance level): tracking data items (e.g., a tuple in a dataset) transformations
  * _Coarse-grained_ (schema-level): tracking dataset transformations
* Queries
  * _Where_ provenance: given some output, which inputs did the output come from?
  * _How_ provenance: given some output, how were the inputs manipulated?
  * _Why_ provenance: given some output, why was data generated?
    * E.g., in the form of a proof tree that locates source data items contributing to its creation

Simmhan, Yogesh L., Beth Plale, and Dennis Gannon. "A survey of data provenance techniques."  _Computer Science Department, Indiana University, Bloomington IN_ 47405 (2005): 69.

Ikeda, Robert, and Jennifer Widom.  _Data lineage: A survey_ . Stanford InfoLab, 2009.

# Data provenance

* Data provenance, an example of data management
  * Metadata pertaining to the history of a data item
  * Pipeline including the origin of objects and operations they are subjected to
  * We have a standard: [https://www.w3.org/TR/prov-dm/](https://www.w3.org/TR/prov-dm/)

![](imgs/slides16.png)

[https://www.w3.org/TR/prov-dm/](https://www.w3.org/TR/prov-dm/)

# Data provenance

* _Entity_
  * Physical/conceptual things
* _Activity_
  * Dynamic aspects of the world, such as actions
  * How entities come into existence, often making use of previously existing entities
* _Agent_
  * A person, a piece of software
  * Takes a role in an activity such that the agent can be assigned some degree of responsibility for the activity taking place

![](imgs/slides17.png)

[https://www.w3.org/TR/2013/NOTE-prov-primer-20130430/](https://www.w3.org/TR/2013/NOTE-prov-primer-20130430/)

# Data provenance

* Use cases for data provenance
* Accountability and auditing
* Data quality
  * Monitoring of the quality (e.g., accuracy) of the objects produced
  * Notify when a transformation pipeline is not behaving as expected
* Debugging
  * Inferring the cause of pipeline failures is challenging
  * Store inputs of each operation with versions and environmental settings (RAM, CPUs, etc.)
* And so on...

# Compression

* Summarization / compression
  * Present a concise representation of a dataset in a comprehensible and informative manner

![](imgs/slides18.png)

Ahmed, Mohiuddin. "Data summarization: a survey."  _Knowledge and Information Systems_ 58.2 (2019): 249-273.

# Data profiling

* Data profiling [@naumann2014data]
  * A broad range of methods to efficiently analyze a given data set
  * E.g., in a _relational_ scenario, _tables_ of a relational database are _scanned_ to derive _metadata_, such as _data types_, _completeness_ and _uniqueness_ of columns, _keys_ and  _foreign keys_, and occasionally _functional dependencies_ and _association rules_

![](imgs/slides19.png)

# Data profiling

* Use cases
  * _Query optimization_
    * Performed by DBMS to support query optimization with statistics about tables and columns
    * Profiling results can be used to estimate the selectivity of operators and the cost of a query plan
  * _Data cleansing _ (typical use case is profiling data)
    * Prepare a cleansing process by revealing errors (e.g., in formatting), missing values or outliers
  * _Data integration and analytics_
* Challenges?

# Data profiling

:::: {.columns}
::: {.column width=50%}

* Challenges
  * The results of data profiling are _computationally complex_ to discover
    * E.g., discovering keys/dependencies usually involves some sorting step for each considered column
  * Verification of _complex constraints on column combinations _ in a database
    * What is the complexity of this task?

:::
::: {.column width=50%}

| a | b | c | d |
|:-: |:-: |:-: |:-: |
| 1 | 1 | 2 | 2 |
| 1 | 2 | 1 | 4 |

Given a table with columns $C = { a, b, c, d }$

- To extract the (distinct) cardinality of each column, I will consider $|C|$ columns $\{(a), (b), (c), (d)\}$
- To extract the correlations between pairs of columns, I will consider ($\binom{|C|}{n}$) groups $\{(a, b), (a, c), (a, d), (b, c), ...\}$
- Extracting the relationships among all possible groups of columns generalizes to $\sum_{n=1}^{|C|}\binom{|C|}{n}=2^{|C|}−1$ groups

:::
::::

# Entity resolution

* Entity resolution
  * (also known as entity matching, linking)
  * Find records that refer to the same entity across different data sources (e.g., data files, books, websites, and databases)

![](imgs/slides20.png)

Papadakis, George, et al. "Blocking and filtering techniques for entity resolution: A survey."  _ACM Computing Surveys (CSUR)_ 53.2 (2020): 1-42.

# Data versioning

* Version control
  * A class of systems responsible for managing changes to computer programs, documents, or data collections
  * Changes are identified by a number/letter code, termed the revision/version number
* However, data pipelines are not only about code bult also about
  * Model Version control
  * Data Version Control
  * Model Parameter Tracking
  * Model Performance Comparison

![](imgs/slides21.png)

Support CRUD (Create, Read, Update, Delete) operations with versions

E.g., on AWS (PUT, GET, DELETE), what about update?

![](imgs/slides22.png)

![](imgs/slides23.png)

![](imgs/slides24.png)

[https://docs.aws.amazon.com/AmazonS3/latest/userguide/versioning-workflows.html](https://docs.aws.amazon.com/AmazonS3/latest/userguide/versioning-workflows.html) (accessed 2022-08-01)

# In action

![](imgs/slides25.png)

Lab: California housing prices

# Data platform

* Are we done? No!
  * Metadata can become bigger than data themselves
* We need meta meta-data (or models)...
  * ... chasing our own tails
* Data management is still a (research) issue in data platforms

# Data lakehouse

* __Data __ __lakehouse__
  * Data management architecture that combines the flexibility, cost-efficiency, and scale of data lakes with the data management and ACID transactions of data warehouses, enabling business intelligence (BI) and machine learning (ML) on all data
  * Vendor lock in

![](imgs/slides26.png)

[https://www.databricks.com/glossary/data-lakehouse](https://www.databricks.com/glossary/data-lakehouse)

![](imgs/slides27.png)

|  | Data warehouse | Data lake | Data lakehouse |
|:-: |:-: |:-: |:-: |
| Data format | Closed, proprietary format | Open format (e.g., Parquet) | Open format |
| Types of data | Structured data, with limited support for semi-structured data | All types: Structured data, semi-structured data, textual data, unstructured (raw) data | All types: Structured data, semi-structured data, textual data, unstructured (raw) data |
| Data access | SQL-only, no direct access to file | Open APIs for direct access to files with SQL, R, Python and other languages | Open APIs for direct access to files with SQL, R, Python and other languages |
| Reliability | High quality, reliable data with ACID transactions | Low quality, data swamp | High quality, reliable data with ACID transactions |
| Governance and security | Fine-grained security and governance for row/columnar level for tables | Poor governance as security needs to be applied to files | Fine-grained security and governance for row/columnar level for tables |
| Performance | High | Low | High |
| Scalability | Scaling becomes exponentially more expensive | Scales to hold any amount of data at low cost, regardless of type | Scales to hold any amount of data at low cost, regardless of type |
| Use case support | Limited to BI, SQL applications and decision support | Limited to machine learning | One data architecture for BI, SQL and machine learning |

* Key technologies used to implement open source Data Lakehouses
  * Databricks’ Delta Lake
  * Apache Hudi
  * Apache Iceberg

[https://databricks.com/blog/2021/05/19/evolution-to-the-data-lakehouse.html](https://databricks.com/blog/2021/05/19/evolution-to-the-data-lakehouse.html)

# Data platform

__Is it a Lakehouse with another name?__

  * A Lakehouse is a part of data platform, a layer that enables to query multiple data sources (with SQL/Spark) transparently by using some metadata (JSON) log
  * Still, you could get a data platform where such transparence is not mandatory or could be achieved by different techniques (e.g., multistore [1])

[1] Forresi, C., Gallinucci, E., Golfarelli, M., & Hamadou, H. B. (2021). A dataspace-based framework for OLAP analyses in a high-variety multistore. The VLDB Journal, 30(6), 1017-1040.

__Is it a new name for BI?__

No, in a data platform you also need to manage (streams of) operational data and OLTP workloads

![](imgs/slides28.png)

# Data platform: related job positions

* _Data platform engineer_
  * Orchestrate the successful implementation of cloud technologies within the data infrastructure of their business
  * Solid understanding of impact database types and implementation
  * Responsible for purchasing decisions for cloud services and approval of data architectures
* _Data architect_
  * Team members who understand all aspects of a data platform's architecture
  * Work closely with the data platform engineers to create data workflows
  * Responsible for designing and testing new database architectures and planning both data and architecture migrations
* _Data pipeline engineer_
  * Responsible for planning, architecting, and building large-scale data processing systems
* _Data analyst_
  * Analyze data systems, creating automated systems for retrieving data from the data platform
  * Cloud data analysts are more commonly members of the business user population
* _Data scientist_
  * Analyze and interpret complex digital data
  * Work with new technologies (e.g., machine learning) to deepen the business' understanding and gain new insights

# From DevOps...

__DevOps__ combines development and operations to increase the efficiency, speed, and security of software development and delivery compared to traditional processes.

DevOps practices enable software development (dev) and operations (ops) teams to accelerate delivery through automation, collaboration, fast feedback, and iterative improvement

![](imgs/slides29.png)

[https://about.gitlab.com/topics/devops/](https://about.gitlab.com/topics/devops/) (accessed 2023-06-03)

![](imgs/slides30.png)

# ... to DataOps

__DataOps__ refers to a general process aimed to shorten the end-to-end data analytic life-cycle time by introducing automation in the data collection, validation, and verification process

![](imgs/slides31.png)

Munappy, A. R., Mattos, D. I., Bosch, J., Olsson, H. H., & Dakkak, A. (2020, June). From ad-hoc data analytics to dataops. In _Proceedings of the International Conference on Software and System Processes_  (pp. 165-174).

# DataOps

![](imgs/slides32.png)

* From DevOps to DataOps
  * _“A collaborative data management practice focused on improving the _ _communication, integration and automation of data flows between _ _data managers and data consumers across an organization”_
  * Data analytics improved in terms of velocity, quality, predictability and scale of software engineering and deployment
* Some key rules
  * Establish progress and performance measurements at every stage
  * Automate as many stages of the data flow as possible
  * Establish governance discipline (_governance-as-code_)
  * Design process for growth and extensibility

![](imgs/slides33.png)

Gartner, 2020 [https://www.gartner.com/smarterwithgartner/how-dataops-amplifies-data-and-analytics-business-value](https://www.gartner.com/smarterwithgartner/how-dataops-amplifies-data-and-analytics-business-value)Andy Palmer, 2015 [https://www.tamr.com/blog/from-devops-to-dataops-by-andy-palmer/](https://www.tamr.com/blog/from-devops-to-dataops-by-andy-palmer/) William Vorhies, 2017 [https://www.datasciencecentral.com/profiles/blogs/dataops-it-s-a-secret](https://www.datasciencecentral.com/profiles/blogs/dataops-it-s-a-secret)

# Data fabric

* “vision for data management [...] that seamlessly connects different clouds, whether they are private, public, or hybrid environments.” (2016)
* Frictionless access and sharing of data in a distributed data environment
  * Enables a __single and consistent data management framework__ , which allows seamless data access and processing by design across otherwise siloed storage
  * Leverages __human and machine capabilities to access data __ in place or support its consolidation where appropriate
  * __Continuously identifies and connects data __ from disparate applications to discover unique, business-relevant relationships between the available data points
* It is a unified architecture with an integrated set of technologies and services
  * Designed to deliver integrated and enriched data – at the right time, in the right method, and to the right data consumer – in support of both operational and analytical workloads
  * Combines key data management technologies – such as __data catalog__ , __data governance__ , __data integration__ , __data pipelining__ , and __data orchestration__

[https://cloud.netapp.com/hubfs/Data-Fabric/Data%20Fabric%20WP%20April%202017.pdf](https://cloud.netapp.com/hubfs/Data-Fabric/Data%20Fabric%20WP%20April%202017.pdf) (accessed 2023-06-23)Gartner, 2019 [https://www.gartner.com/en/newsroom/press-releases/2019-02-18-gartner-identifies-top-10-data-and-analytics-technolo](https://www.gartner.com/en/newsroom/press-releases/2019-02-18-gartner-identifies-top-10-data-and-analytics-technolo) Gartner, 2021 [https://www.gartner.com/smarterwithgartner/data-fabric-architecture-is-key-to-modernizing-data-management-and-integration](https://www.gartner.com/smarterwithgartner/data-fabric-architecture-is-key-to-modernizing-data-management-and-integration) K2View Whitepaper: What is a Data Fabric? The Complete Guide, 2021

  * __Catalog all your data__: including business glossary and design-time and runtime metadata
  * __Enable self-service capabilities__: data discovery, profiling, exploration, quality assessment, consumption of data-as-a-product
  * __Provide a knowledge graph__: Visualizing how data, people, processes, systems, etc. are interconnected, deriving additional actionable insight
  * __Provide intelligent (smart) information integration__: Supporting IT staff and business users alike in their data integration and transformation, data virtualization, and federation tasks
  * __Derive insight from metadata__: Orchestrating and automating tasks and jobs for data integration, data engineering, and data governance end to end
  * __Enforce local and global data rules/policies__: Including AI/ML-based automated generation, adjustments, and enforcement of rules and policies
  * __Manage an end-to-end unified lifecycle__: Implementing a coherent and consistent lifecycle end to end of all Data Fabric tasks across various platforms, personas, and organizations
  * __Enforce data and AI governance__: Broadening the scope of traditional data governance to include AI artefacts, for example, AI models, pipelines

Is this brand new?

* __It is a design concept__
  * It optimizes data management by automating repetitive tasks
  * According to Gartner estimates, 25% of data management vendors will provide a complete framework for data fabric by 2024 – up from 5% today

![](imgs/slides34.png)

![](imgs/slides35.png)

Gartner, 2021 [https://www.gartner.com/smarterwithgartner/data-fabric-architecture-is-key-to-modernizing-data-management-and-integration](https://www.gartner.com/smarterwithgartner/data-fabric-architecture-is-key-to-modernizing-data-management-and-integration)

K2View, 2021 [https://www.k2view.com/top-data-fabric-vendors](https://www.k2view.com/top-data-fabric-vendors)

---

Top Players 
https://solutionsreview.com/data-management/the-best-data-fabric-tools-and-software/ 
https://em360tech.com/top-10/data-modelling-fabric 
Predictions
https://live-datastaxd8.pantheonsite.io/sites/default/files/2021-02/Predicts_2021_Data__735776_ndx.pdf

![](imgs/slides36.png)

[https://www.irion-edm.com/data-management-insights/gartner-data-summit-irion-representative-vendor-for-data-fabric-technology/](https://www.irion-edm.com/data-management-insights/gartner-data-summit-irion-representative-vendor-for-data-fabric-technology/)

![](imgs/slides37.png)

Gartner, 2021 [https://www.gartner.com/smarterwithgartner/data-fabric-architecture-is-key-to-modernizing-data-management-and-integration](https://www.gartner.com/smarterwithgartner/data-fabric-architecture-is-key-to-modernizing-data-management-and-integration)

# Data mesh

* Distributed data architecture, under centralized governance and standardization for interoperability, enabled by a shared and harmonized self-serve data infrastructure
  * Domain-oriented decentralized data ownership
    * Decentralization and distribution of responsibility to people who are closest to the data, in order to support continuous change and scalability
    * Each domain exposes its own op/analytical APIs
  * __Data as a product __ (_quantum_)
    * Products must be discoverable, addressable, trustworthy, self-describing, secure
  * Self-serve data infrastructure as a platform
    * High-level abstraction of infrastructure to provision and manage the lifecycle of data products
  * Federated computational governance
    * A governance model that embraces decentralization and domain self-sovereignty, interoperability through global standardization, a dynamic topology, automated execution of decisions by the platform

Zhamak Dehghani, 2019 [https://martinfowler.com/articles/data-monolith-to-mesh.html](https://martinfowler.com/articles/data-monolith-to-mesh.html)Zhamak Dehghani, 2020 [https://martinfowler.com/articles/data-mesh-principles.html](https://martinfowler.com/articles/data-mesh-principles.html)

---

https://www.youtube.com/watch?v=_bmYXWCxF_Q

* Data Mesh organizes data around __business domain owners __ and transforms relevant data assets (data sources) to __data products__ that can be consumed by distributed business users from various business domains or functions
  * Data products are created, governed, and used in an __autonomous, decentralized__ , and self-service manner
  * __Self-service capabilities__ , which we have already referenced as a Data Fabric capability, enable business organizations to entertain a data marketplace with shopping-for-data characteristics

![](imgs/slides38.png)

# What makes data a product?

* A __data product __ is raw data transformed into a business context
  * Data products are registered in __knowledge catalog __ through specifications (XML, JSON, etc.)
  * Main features
    * __Data product description__: The data product needs to be well described
    * __Access methods__: for example, REST APIs, SQL, NoSQL, etc., and where to find the data asset
    * __Policies and rules__: who is allowed to consume the data product for what purpose
    * __SLAs__: agreements regarding the data product availability, performance characteristics, functions, cost of data product usage
    * __Defined format__: A data product needs to be described using a defined format
    * __Cataloged__: All data products need to be registered in the knowledge catalog. Data products need to be searchable and discoverable by potential data product consumers and business user
  * Data products themselves are not stored in the knowledge catalog

# Data mesh vs data fabric

* They are design concepts, not things
  * They are not mutually exclusive
  * They are architectural frameworks, not architectures
    * The frameworks must be adapted and customized to your needs, data, processes, and terminology
    * Gartner estimates 25% of data management vendors will provide a complete data fabric solution by 2024 – up from 5% today

Alex Woodie, 2021 [https://www.datanami.com/2021/10/25/data-mesh-vs-data-fabric-understanding-the-differences/](https://www.datanami.com/2021/10/25/data-mesh-vs-data-fabric-understanding-the-differences/) Dave Wells, 2021 [https://www.eckerson.com/articles/data-architecture-complex-vs-complicated](https://www.eckerson.com/articles/data-architecture-complex-vs-complicated)

* Both provide an architectural framework to access data across multiple technologies and platforms
  * __Data fabric__
    * Attempts to centralize and coordinate data management
    * Tackles the complexity of data and metadata in a smart way that works well together
    * Focus on the architectural, technical capabilities, and intelligent analysis to produce active metadata supporting a smarter, AI-infused system to orchestrate various data integration styles
  * __Data mesh__
    * Emphasis on decentralization and data domain autonomy
    * Focuses on organizational change; it is more about people and process
    * Data are primarily organized around domain owners who create business-focused data products, which can be aggregated and consumed across distributed consumers

Alex Woodie, 2021 [https://www.datanami.com/2021/10/25/data-mesh-vs-data-fabric-understanding-the-differences/](https://www.datanami.com/2021/10/25/data-mesh-vs-data-fabric-understanding-the-differences/) Dave Wells, 2021 [https://www.eckerson.com/articles/data-architecture-complex-vs-complicated](https://www.eckerson.com/articles/data-architecture-complex-vs-complicated)

![](imgs/slides39.png)

* Data Fabric and Mesh are the results from the data architecture evolution
  * __Many capabilities were in existence already long before__ the terms were coined
* Take away:
  * Abstract the “building blocks” of such platforms
  * Let them evolve according to scalability and flexibility requirements

# (Some) References

![](imgs/slides40.jpg)

![](imgs/slides41.png)

![](imgs/slides42.png)

# «Example» of architecture

![](imgs/slides43.jpg)

[1] [https://xkcd.com/2347/](https://xkcd.com/2347/) (*)(*) «Ormai sta xkcd é una base troppo usata» Alessandro Tappi

# Example of data platform: Hadoop-based

* A data platform on the Hadoop stack requires several tools
* How many levels of complexity are hidden here?
* How do you provision it?
  * Manual provisioning on-premises
  * Semi-automatic provisioning on-premises
  * Automatic provisioning in the cloud

Storage   .

Resources   .

Application   .

GUI   .

Messaging   .

Orchestration   .

Map Reduce

Batch

Flink

real-time

# On-premises manual provisioning

* Hardly advisable, if not for small and local tests
  * __Technical challenges__
    * Installation: how do I set up a new machine?
    * Networking: how do I cable dozens of machines?
    * Management: how do I replace a broken disk?
    * Upgrade: how do I extend the cluster with new services/machines?
    * (energy and cooling, software licenses, insurance...)
  * __Technological challenges__
    * How do we configure a distributed environment?
    * How do we set up/integrate/control independent services?
    * How do we orchestrate data flows?
  * __Business challenges__
    * Can we afford to spend resources on tasks that are not mission oriented?
    * No free lunch, each choice has cost/benefit
    * How much time does it take to master a technology?
    * How many people do I need?

# Example of data platform: MOSES

![](imgs/slides44.png)

* Example of a data platform (MOSES)
* Functional architecture
  * Components of MOSES are in orange
  * Others are standard components in charge of producing/consuming, processing, storing, and visualizing data
  * The orchestrator (e.g., Oozie) manages (e.g., schedules) the data transformation processes

Metadata Extractor

![](imgs/slides45.png)

![](imgs/slides46.png)

Metadata Search

Engine

![](imgs/slides47.png)

![](imgs/slides48.png)

![](imgs/slides49.png)

![](imgs/slides50.png)

Provenance Manager

![](imgs/slides51.png)

![](imgs/slides52.png)

![](imgs/slides53.png)

![](imgs/slides54.png)

Custom components

![](imgs/slides55.png)

![](imgs/slides56.png)

![](imgs/slides57.png)

![](imgs/slides58.png)

![](imgs/slides59.png)

![](imgs/slides60.png)

![](imgs/slides61.png)

Process Interfaces

MOSES Interfaces

Other Interfaces

Workflow Administration

Francia, M., Gallinucci, E., Golfarelli, M., Rizzi, S. et al. (2021). Making data platforms smarter with MOSES. Future Generation Computer Systems, 125, 299-313.

# Summing up

  * Storage should be flexible enough to support heterogenous data models and raw data
    * From operational databases to DWHs __(why?)__
    * From relational data models to NoSQL __(why?)__
    * Data lake to (directly) ingest raw data
  * Storage,  _per se_ , is insufficient to get value from the data __(examples?)__
    * We also need data processing and fruition
    * Data lakes are blurring into data platforms
  * Data platforms support end-to-end data needs __(which ones?)__
    * Building data platforms is hard __(why?)__
    * Managing data platforms is hard, exploit meta-data to ease this task
      * Data lineage, compression, profiling, resolution, etc.
  * __Open question__: how do we deploy working data platforms?

# -- newsection --

# Building data pipelines

---

https://catalog.us-east-1.prod.workshops.aws/workshops/ea7ddf16-5e0a-4ec7-b54e-5cadf3028b78/en-US

# A necessary introduction

* Computational thinking: solving problems using concepts and ideas from computer science.
  * Take a complex problem
  * Understand better what the problem involves
  * Develop possible solutions
  * Present these solutions in a way that a computer, human or both can understand
* Pillars to computational thinking:
  * Decomposition
  * Pattern recognition
  * Data representation
  * Abstraction

![](imgs/slides62.png)

# Computational thinking

* __Decomposition__
  * Taking a complex problem and breaking it into more manageable sub-problems.
  * The solution to each sub-problem may be much simpler by putting together the solutions to the sub-problems (any example?)
* __Pattern recognition__
  * Find patterns among the sub-problems
  * Identify problems sharing similarities or characteristics
  * Discovering these patterns make the complex problem easier to solve since we can use the same solution for each occurrence of the pattern (any example?)

* Data __representation__ and __abstraction__
  * Determining the important characteristics of the problem and filtering out those that are not
  * Can create a representation of what we're trying to solve
* __Algorithm__
  * A set of step-by-step instructions of how to solve a problem.
  * It identifies what is to be done (the instructions), and the order in which they should be done
* ... there is no magic in programming computers

# Integrated analytics lab

* Requirements:
  * Knowledge of programming, data structures, and algorithms
  * Acquaintance with Python programming and notebooks
* The labs will be mainly guided...
  * ... but the notebooks contain all the details
  * ... no time for a complete (coding) discussion during the lectures
* Focus on the problem __understanding__ , __definition__ , and __solution__ !

* Building data pipelines
  * Frame the problem and look at the big picture
  * Get the data
  * Explore the data to gain insights
  * Prepare the data
  * Explore different models and find the best ones
  * Fine-tune your models
  * Present your solution
  * Launch, monitor, and maintain your system

![](imgs/slides63.png)

* Building data pipelines
  * _Frame the problem_ and look at the big picture
  * _"We’ll use the California Housing Prices. Our task is to use California census data to forecast housing prices given the population, median income, and median housing price for each block group in California. Block groups are the smallest geographical unit for which the US Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people)"_

![](imgs/slides64.png)

![](imgs/slides65.png)

![](imgs/slides66.png)

* Building data pipelines
  * Frame the problem and look at the big picture
    * _Knowing the objective_ is important because it will determine how you frame the problem, which algorithms you will select, which performance measure you will use to evaluate your model, and how much effort you will spend tweaking it.
    * _"Your boss answers that your model’s output (a prediction of a district’s median housing price) will be fed to another Machine Learning system, along with many other signals. This downstream system will determine whether it is worth investing in a given area or not. Getting this right is critical, as it directly affects revenue."_

![](imgs/slides67.png)

* Building data pipelines
  * Frame the problem and look at the big picture
    * ✔Define the objective in business terms
    * ✖How should performance be measured? (postponed for later)
  * Get the data
    * ✔ List the data you need and how much you need
      * Data could be available in a relational database and/or spread across multiple tables/documents/files
      * In this project, however, things are much simpler
  * Explore the data to gain insights
    * ✔ Create an environment to keep track of your data exploration
      * You have been provided with notebook environments
    * _✔ Study each attribute and its characteristics_
      * _Let's do this!_

# In action

![](imgs/slides68.png)

# STORAGE: NoSQL DBMSs

# Not only SQL

# Introduction

What is NoSQL

Where does it come from, and why

# Strengths of RDBMSs

* _ACID properties_
  * Provides guarantees in terms of consistency and concurrent accesses
* _Data integration and normalization of schemas_
  * Several application can share and reuse the same information
* _Standard model and query language_
  * The relational model and SQL are very well-known standards
  * The same theoretical background is shared by the different implementations
* _Robustness_
  * Have been used for over 40 years

# Weaknesses of RDBMS

* Impedance mismatch
  * Data are stored according to the relational model, but applications to modify them typically rely on the object-oriented model
  * Many solutions, no standard
    * E.g.: Object Oriented DBMS (OODBMS), Object-Relational DBMS (ORDBMS), Object-Relational Mapping (ORM) frameworks
* _Painful scaling-out_
  * Not suited for a cluster architecture
  * Distributing an RDBMS is neither easy nor cheap (e.g., Oracle RAC)
* _Consistency vs latency_
  * Consistency is a must – even at the expense of latency
  * Today's applications require high reading/writing throughput with low latency
* _Schema rigidity_
  * Schema evolution is often expensive

# What NoSQL means

* The term has been first used in '98 by Carlo Strozzi
  * It referred to an open-source RDBMS that used a query language different from SQL
* In 2009 it was adopted by a meetup in San Francisco
  * Goal: discuss open-source projects related to the newest databases from Google and Amazon
  * Participants: Voldemort, Cassandra, Dynomite, HBase, Hypertable, CouchDB, MongoDB
* Today, _NoSQL_ indicates _DBMSs_ adopting a _different data model from the relational one_
  * NoSQL = Not Only SQL
  * According to Strozzi himself, NoREL would have been a more proper noun

# The first NoSQL systems

* _LiveJournal, 2003_
  * Goal: reduce the number of queries on a DB from a pool of web servers
  * Solution: _Memcached_ , designed to keep queries and results in RAM
* _Google, 2005_
  * Goal: handle Big Data (web indexing, Maps, Gmail, etc.)
  * Solution: _BigTable_ , designed for scalability and high performance on Petabytes of data
* _Amazon, 2007_
  * Goal: ensure availability and reliability of its e-commerce service 24/7
  * Solution: _DynamoDB_ , characterized by strong simplicity for data storage and manipulation

---

https://en.wikipedia.org/wiki/LiveJournal LiveJournal è una sorta di MSN russo

# NoSQL common features

* Not just rows and tables
  * Several data model adopted to store and manipulate data
* Freedom from joins
  * Joins are either not supported or discouraged
* Freedom from rigid schemas
  * Data can be stored or queried without pre-defining a schema (_schemaless_ _ or _soft-schema_)
* Distributed, shared-nothing architecture
  * Trivial scalability in a distributed environment with no performance decay
  * Each workstation uses its own disks and RAM
* SQL is dead, long live SQL!
  * Some systems do adopt SQL (or a SQL-like language)

# NoSQL in the Big Data world

* _NoSQL_ systems are mainly used for operational workloads (_OLTP_)
  * Optimized for high read and write throughput on small amounts of data
* _Big Data _ technologies are mainly used for analytical workloads (_OLAP_)
  * Optimized for high read throughput on large amounts of data
* Can NoSQL systems be used for OLAP?
  * Possibly, but through Big Data analytical tools (e.g., Spark)

---

https://aws.amazon.com/it/nosql/

# Data models

# NoSQL: several data models

One of the key challenges is to understand which one fits best with the required application

| Model | Description | Use cases |
|:-: |:-: |:-: |
| Key-value | Associates any kind of value to a string | Dictionary, lookup table, cache, file and images storage |
| Document | Stores hierarchical data in a tree-like structure | Documents, anything that fits into a hierarchical structure |
| Wide-column | Stores sparse matrixes where a cell is identified by the row and column keys | Crawling, high-variability systems, sparse matrixes |
| Graph | Stores vertices and arches | Social network queries, inference, pattern matching |

# Running example

Typical use case: customers, orders and products

![](imgs/slides69.png)

# Relational: data model

Based on tables and rows

![](imgs/slides70.png)

# Data modeling example: relational model

![](imgs/slides71.png)

# Graph: data model

* Each DB contains one or more _graphs_
* Each graph contains _vertices _ and _arcs_
  * Vertices: usually represent real-world entities
    * E.g.: people, organizations, web pages, workstations, cells, books, etc.
  * Arcs: represent directed relationships between the vertices
    * E.g.: friendship, work relationship, hyperlink, ethernet links, copyright, etc.
  * Vertices and arcs are described by _properties_
  * Arcs are stored as physical pointers
* Most known specializations:
  * Reticular data model
    * Parent-child or owner-member relationships
  * Triplestore
    * Subject-predicate-object relationships (e.g., RDF)

![](imgs/slides72.png)

---

https://stackoverflow.com/questions/5040617/what-is-the-difference-between-a-graph-database-and-a-network-database

# Graph: querying

* Graph databases usually model relationships-rich scenarios
* The query language simplifies the navigation of these relationships
  * Support for transactions
  * Support for indexes, selections and projections
  * __Query language based on detecting patterns__

| Query | Pattern |
|:-: |:-: |
| Find friends of friends | (user)-[:KNOWS]-(friend)-[:KNOWS]-(foaf) |
| Find shortest path from A to B | shortestPath((userA)-[:KNOWS*..5]-(userB)) |
| What has been bought by those who bought my same products? | (user)-[:PURCHASED]->(product)<-[:PURCHASED]-()-[:PURCHASED]->(otherProduct) |

# Data modeling example: graph model

IDs are implicitly handled; different edge colors imply different edge types

![](imgs/slides73.png)

CardN: 457

txnId:....

CardN: 477

txnId:....

street:Adamcity:Chicago

state:illinois

code:60007

street:9thcity:NewYork

state:NewYork

code:10001

# Graph vs Aggregate modeling

* The graph data model is intrinsically different from the others
  * Focused on the relationships rather than on the entities per-se
  * __Limited scalability__: it is often impossible to shard a graph on several machines without "cutting" several arcs (i.e. having several cross-machine links)
    * Batch cross-machine queries: don’t follow relationships one by one, but "group them" to make less requests
    * Limit the depth of cross-machine node searches
  * _Data-driven modeling_
* Key-value, document and wide-column are called _aggregate-oriented_
  * Aggregate = key-value pair, document, row (respectively)
  * The aggregate is the atomic block (no guarantees for multi-aggregate operations)
* Based on the concept of encapsulation
  * Avoid joins as much as possible  achieve __high scalability__
    * Con: data denormalization  __potential inconsistencies in the data__
  * _Query-driven modeling_

---

https://stackoverflow.com/questions/21558589/neo4j-sharding-aspect 
https://ayende.com/blog/4490/that-no-sql-thing-scaling-graph-databases

# Document: data model

* Each DB contains one or more _collections_ (corresponding to tables)
* Each collection contains a list of _documents_ (usually JSON)
  * Documents are hierarchically structured
* Each document contains a set of _fields_
  * The _ID_ is mandatory
* Each field corresponds to a _key-value pair_
  * Key: unique string in the document
  * Value: either simple (string, number, boolean) or complex (object, array, BLOB)
    * A complex field can contain other field

{

"_id": 1234,

"name": "Enrico",

"address": {

"city": "Cesena",            "postalCode": 47522

},

"contacts": [ {

"type": "office",            "contact": "0547-338835"

}, {

"type": "skype",            "contact": "egallinucci"

} ]

}

# Document: querying

* The query language is quite expressive
  * Can create indexes on fields
  * Can filter on the fields
  * Can return more documents with one query
  * Can select which fields to project
  * Can update specific fields
* Different implementations, different functionalities
  * Some enable (possibly materialized) views
  * Some enable MapReduce queries
  * Some provide connectors to Big Data tools (e.g., Spark, Hive)
  * Some provide _full-text search _ capabilities

# Data modeling example: aggregate model (2)

![](imgs/slides74.png)

![](imgs/slides75.png)

# Data modeling example: document model (1)

Product collection

Customer collection

{

"_id": 1,

"name": "Martin",

"adrs": [

{"street":"Adam", "city":"Chicago", "state":"illinois", "code":60007},       {"street":"9th", "city":"NewYork", "state":"NewYork", "code":10001}

],

"orders": [ {

"orderpayments":[

{"card":477, "billadrs": {"street":"Adam", "city":"Chicago", "state":"illinois", "code":60007}},

{"card":457, "billadrs": {"street":"9th", "city":"NewYork", "state":"NewYork", "code":10001}}

],

"products":[

{"id":1, "name":"Cola", "price":12.4},

{"id":2, "name":"Fanta", "price":14.4}

],

"shipAdrs": {"street":"9th", "city":"NewYork", "state":"NewYork", "code":10001}

}]

}

  * {
  * "_id":1,
  * "name":"Cola",
  * "price":12.4
  * },
  * {
  * "_id":2,
  * "name":"Fanta",
  * "price":14.4
  * }

  * {
  * "_id":1,
  * "name":"Cola",
  * "price":12.4
  * },
  * {
  * "_id":2,
  * "name":"Fanta",
  * "price":14.4
  * }

{

"_id": 1,

"name": "Martin",

"adrs": [

{"street":"Adam", "city":"Chicago", "state":"illinois", "code":60007},       {"street":"9th", "city":"NewYork", "state":"NewYork", "code":10001}

]

}

Customer

collection

* {
* "_id": 1,
* "customer":1,
* "orderpayments":[
* {"card":477, "billadrs":{"street":"Adam", "city":"Chicago", "state":"illinois", "code":60007}},
  * {"card":457, "billadrs":{"street":"9th", "city":"NewYork", "state":"NewYork", "code":10001}}
  * ],
  * "products": [
  * {"id":1, "name":"Cola", "price":12.4},
  * {"id":2, "name":"Fanta", "price":14.4}
  * ],
  * "shipAdrs": {"street":"9th", "city":"NewYork", "state":"NewYork", "code":10001}
* }

Product

collection

Order

collection

# Key-value: data model

* Each DB contains one or more _collections_ (corresponding to tables)
* Each collection contains a list of _key-value pairs_
  * Key: a unique string
    * E.g.: ids, hashes, paths, queries, REST calls
  * Value: a BLOB (binary large object)
    * E.g.: text, documents, web pages, multimedia files
* Looks like a simple dictionary
  * _The collection is indexed by key_
  * _The value may contain several information_
    * Definitions, synonyms and antonyms, images, etc.

![](imgs/slides76.png)

# Key-value: querying

* Three simple kinds of query:
  * _put($key as _ _xs:string_ _, $value as item())_
    * Adds a key-value pair to the collection
    * If the key already exists, the value is replaced
  * _get($key as _ _xs:string_ _) as item()_
    * Returns the value corresponding to the key (if it exists)
  * _delete($key as _ _xs:string_ _)_
    * Deletes the key-value pair
* The value is a _ _black box_ _: it cannot be queried!
  * No "where" clauses
  * No indexes on the values
  * Schema information is often indicated in the key

| Key | Value |
|:-: |:-: |
| user:1234:name | Enrico |
| user:1234:city | Cesena |
| post:9876:written-by | user:1234 |
| post:9876:title | NoSQL Databases |
| comment:5050:reply-to | post:9876 |

# Data modeling example: key-value model

Product collection

Customer collection

| key | value |
|:-: |:-: |
| p-1:name | Cola |
| p-2:name | Fanta |

| key | value |
|:-: |:-: |
| cust-1:name | Martin |
| cust-1:adrs | [ <br />  {"street":"Adam", "city":"Chicago", "state":"Illinois", "code":60007},    {"street":"9th", "city":"NewYork", "state":"NewYork", "code":10001}<br />] |
| cust-1:ord-99 | { <br />  "orderpayments": [ <br />     {"card":477, "billadrs": <br />        {"street":"Adam", "city":"Chicago", "state":"illinois", "code":60007} }, <br />     {"card":457, "billadrs":<br />        {"street":"9th", "city":"NewYork", "state":"NewYork", "code":10001} <br />  ],<br /> "products": [ <br />     {"id":1, "name":"Cola", "price":12.4}, <br />     {"id":2, "name":"Fanta", "price":14.4} <br />  ],<br /> "shipAdrs": {"street":"9th", "city":"NewYork", "state":"NewYork", code":10001}<br />} |

# Wide column: data model

* Each DB contains one or more _column families _ (corresponding to tables)
* Each column family contains a list of _row_ in the form of a key-value pair
  * Key: unique string in the column family
  * Value: a set of _columns_
* Each column is a key-value pair itself
  * Key: unique string in the row
  * Value: simple or complex (_supercolumn_)
* Essentially a 2-dimensional key-value store
* _Rows specify only the columns _ _for which a value exists_
  * Particularly suited for sparse matrixes and many-to-many relationships

![](imgs/slides77.png)

# Wide column: querying

* The query language expressiveness is in between key-value and document data models
  * Column indexes are discouraged
  * Can filter on column values (not always)
  * Can return more rows with one query
  * Can select which columns to project
  * Can update specific columns (not always)
* Given the similarity with the relational model, a _SQL-like _ language is often used

# Wide column: ≠ columnar

* Do not mistake the wide column data model with the columnar storage used for OLAP applications
* Row-oriented
  * Pro: inserting a record is easy
  * Con: several unnecessary data may be accessed when reading a record
* Column-oriented
  * Pro: only the required values are accessed
  * Con: writing a record requires multiple accesses

![](imgs/slides78.png)

![](imgs/slides79.png)

![](imgs/slides80.png)

# Data modeling example: wide-column model

Order details column family

| Ord | CustName | Pepsi | Cola | Fanta | ... |
|:-: |:-: |:-: |:-: |:-: |:-: |
| 1 | Martin |  | 12.4 | 14.4 |  |
| 2 | ... | ... |  |  | ... |

| Ord | OrderPayments |
|:-: |:-: |
| 1 | <br /><br /><br /> |
| 2 | ... |

Order payments column family

| Card | Steet | City | State | Code |
|:-: |:-: |:-: |:-: |:-: |
| 477 | 9th | NewYork | NewYork | 10001 |
| 457 | Adam | Chicago | Illinois | 60007 |

# Aggregate modeling strategy

* The _aggregate _ term comes from Domain-Driven Design
  * An aggregate is a group of tightly coupled objects to be handled as a block
  * Aggregates are the basic unit for data manipulation and consistency management
* Advantages
  * _Can be distributed trivially_
    * Data that should be used together (e.g., orders and details) are stored together
  * _Facilitate the developer's job_
    * By surpassing the impedance mismatch problem
* Disadvantages
  * __No design strategy exists for aggregates__
    * _It only depends on how they are meant to be used_
  * Can optimize only a limited set of queries
  * Data denormalization  possible inconsistencies
* RDBMSs are agnostic from this point of view

# Sharding data

A look behind the curtain

* One of the strengths of NoSQL systems is their _scale-out capability_
  * _ _Aggregate data modeling_ _: _ well suited for being distributed within a cluster
  * NoSQL systems can be used in a _single server environment _ too
    * Graph databases do not scale as well as the others
* Two aspects must be considered when deploying on a cluster
  * __Sharding__: _distributing the data across different nodes_
  * __Replication__: _creating copies of the data on several nodes_

---

As data volumes increase, it becomes more difficult and expensive to
scale up—buy a bigger server to run the database on. A more appealing option is to
scale out—run the database on a cluster of servers. Aggregate orientation fits well
with scaling out because the aggregate is a natural unit to use for distribution.

Quando ha senso l’approccio single-server?
Mole di dati non è enorme 
Si vogliono sfruttare le caratteristiche dei database NoSQL (e.g., schemaless, modello dati)
Un sistema distribuito è inevitabilmente più complesso; non è detto che ne valga sempre la pena


# Sharding

* __Sharding__: _subdividing the data in _ _shards_ _ that are stored in different machines_
  * Intrinsic in a distributed DB
  * Improves the efficiency of the system
    * Read/write operations are distributed
* A good _sharding_ _ strategy _ is __fundamental __ to optimize performances
  * Usually based on one or more fields composing the sharding key

![](imgs/slides81.png)

---

Rimosso: Non dimenticarsi che, nei cluster,si usano macchine meno affidabili – diminuisce la resistenza ai guasti


# Sharding strategy

* Thumbs-up rules for a sharding strategy:
* _ Data-locality: stores the data close to those that need to access them_
  * E.g., store orders of Italian customers in the European data center
* _ Keep a balanced distribution_
  * Each node should have the same percentage of data (more or less)
* _ Keep together the data that must be accessed together_
  * E.g., store each client’s orders in the same node

* Hash strategy: a hash function is used to allocate data to partitions
  * Adopted by DynamoDB and Cassandra
  * Pro: ensures even data distribution across nodes  massive scalability
  * Pro: new nodes can be added without heavy data redistribution
  * Con: range queries become inefficient

![](imgs/slides82.png)

---

https://blog.yugabyte.com/four-data-sharding-strategies-we-analyzed-in-building-a-distributed-sql-database/

* Range strategy: each partition contains a range of sorted data
  * Adopted by HBase
  * Pro: efficiently run range queries that work on the sharding key values
  * Con: global ordering often generates hot spots  risk of bottlenecks
  * Con: ranges are defined a priori and this can determine heavy data redistribution

![](imgs/slides83.png)

---

https://blog.yugabyte.com/four-data-sharding-strategies-we-analyzed-in-building-a-distributed-sql-database/

Auto-sharding: the database distributes the data according to the workload

Beware: redefining (or choosing later) the sharding strategy can be quite expensive

![](imgs/slides84.png)

# Replication

* __Replication__: the data is _copied _ on several nodes
  * Improves the robustness of the system
    * In case of node failure, replicas prevent data loss
  * Improves the efficiency of the system
    * More users read the same data from different copies, in parallel
    * Higher chance of enforcing data-locality
* How to distribute the replicas?
  * Random (possibly _topology-aware_) distribution of each record
    * Similarly to HDFS blocks
  * Replication of entire instances
* Main issue: each update must be pushed to every replica
  * Two techniques to handle updates: master-slave, peer to peer

---

Parliamo di replica completa, per ora

# Master-Slave Replication

* _Master_
  * It’s the manager of the data
  * _Handles each and every write operation_
  * Can be chosen or drawn
* _Slaves _
  * Enable read operations
  * In sync with the master
  * Can become masterif the latter fails

![](imgs/slides85.png)

---

Parliamo di replica completa, per ora

* __Pros__
  * Easily handles many read requests
    * Slaves do not need the master to perform reads
  * Useful when the workload mainly consists of reads
  * Useful to avoid write conflicts
* __Cons__
  * _The master is a bottleneck_
    * __Only the master can handle writes__
    * In case of failure, a new master must be drawn
  * Delay in write propagation can be a source of inconsistency
    * Two users may read different values at the same time
    * _Read inconsistency can be problematic, but are relatively limited in time_
  * Not ideal when the workload mainly consists of writes

# Peer-to-Peer Replication

Each node has the same importance

_Each node can handle write operations_

The loss of a node does not compromise reads nor writes

![](imgs/slides86.png)

* __Pro__
  * The failure of a node does not interrupt read nor write requests
  * Write performances easily scale by adding new nodes
* __Cons__
  * _Conflicts! _
  * Delay in write propagation can be a source of inconsistency
    * Same as with master-slave replication
  * Two users may update the same value from different replicas
    * _Write inconsistencies are way worse_

---

TODO: come gestire conflitti in scrittura? Quorum, l‘ultimo vince o segnalazione.

# Handling conflicts

* Read conflicts
  * _Tolerate conflicts_: _ _ the _inconsistency window _ is usually limited
  * _Read-your-writes_: read consistency is guaranteed for the data written by the same user
    * Applies only to reads that immediately follow a write operation
    * One way is to associate a user to a node (risk: unbalanced workloads)
    * Typically, versioning fields are used to ensure that the up-to-date version is read
* Write conflicts (P2P model)
  * _Last write wins: _ in case of conflict, the latest update overrides the others
  * _Conflict prevention_: enforce writes on the most recent version by verifying that the value hasn’t changed since the last read
  * _Conflict detection_: preserve history, merge results, and let the user decide

---

Read-your-writes: https://jepsen.io/consistency/models/read-your-writes
https://highlyscalable.wordpress.com/2012/09/18/distributed-algorithms-in-nosql-databases/
Prevention: verify that the value hasn’tchanges since the last read

# The quorum mechanism

* The _quorum mechanism _ ensures consistent IO under replication
  * Based on contacting a majority of the nodes responsible for certain data
  * The quorum is the minimum number of nodes that a distributed operation has to obtain in order to be allowed to perform an operation on a replicated data item
* Each data item has N replicas
  * Writing quorum: W > N/2
    * The write operation is allowed only if W replicas can be updated
    * Ensures that two write operations cannot occur concurrently
  * Reading quorum: R > N-W
    * The read operation is allowed only if R replicas can be read
    * Ensures that (at least) one copy with the up-to-date value is read

writes _w_ _1_ ,  _w_ _2_ , w 3

|  |
|:-: |
|  |
|  |
|  |
|  |

|  |
|:-: |
|  |
|  |
|  |
|  |

|  |
|:-: |
|  |
|  |
|  |
|  |

|  |
|:-: |
|  |
|  |
|  |
|  |

# Managing consistency

A look behind the curtain

# RDBMS vs NoSQL: different philosophies

* RDBMS come from decades of widespread usage
  * Strong focus on data consistency
  * Years of research activities to optimize performances
  * Highly complex systems (triggers, caching, security, etc.)
* NoSQL systems are designed to succeed where RDBMSs fail
  * Strong focus on data sharding and high availability
  * Quite simple systems (for now)
  * Speed and manageability rather than consistency at all costs

![](imgs/slides87.png)

# Consistency: an example

* Consider 1000€ to be transferred from bank account A to B; the transfer is made by:
  * Removing 1000€ from A
  * Adding 1000€ to B
* What should never happen
  * The money is removed from A but not added to B
  * The money is added twice to B
  * A query on the database shows an intermediate state
    * E.g., A+B = 0€
* RDBMS adopt _transactions _ to avoid this kind of issue

# Consistency in RDBMSs: ACID

* Transactions guarantee four fundamental properties: ACID
* _A_ _tomicity_
  * The transaction is indivisible: either it fully completes, or it fails
  * It cannot be completed partially
* _C_ _onsistency_
  * The transaction leaves the DB in a consistent state
  * Integrity constraints can never be violated
* _I_ _solation_
  * The transaction is independent from the others
  * In case of concurrent transactions, the effect is the same of their sequential execution
* _D_ _urability_
  * The DBMS protects the DB from failures

* Implementation of ACID properties relies on _locking mechanisms and logs_
  * Resources are locked, updates are logged
  * In case of problems, rollback to the original state
  * If no error occurs, unlock the resources
* Consistency is guaranteed to the detriment of speed and availability
  * User may have to wait
  * Hard to replicate this mechanism in a distributed environment
* But, sometimes, consistency is not that important
  * E.g.: e-commerce application
  * Shopping cart management requires speed and availability
  * Order emission requires consistency

# Consistency in NoSQL

* Several attempts have been made to describe NoSQL properties with respect to ACID properties
  * CAP theorem
  * PACELC theorem
  * BASE philosophy
* They are not properties on which NoSQL systems rely
  * Rather, they simply _try _ to describe their behavior

# Consistency in NoSQL: CAP

* "Theorem": only two of the following three properties can be guaranteed
* _C_ _onsistency: _ the system is always consistent
  * Every node returns the same, most recent, successful write
  * Every client has the same view of the data
* _A_ _vailability: _ the system is always available
  * Every non-failing node returns a response for all read and write requests in a reasonable amount of time
* _P_ _artition tolerance: _ the system continues to function and upholds its consistency guarantees in spite of network partitions
  * _In distributed systems, network partitioning_ _is inevitably a possibility_

![](imgs/slides88.png)

---

CAP demonstration: https://dl.acm.org/doi/pdf/10.1145/564585.564601?casa_token=m69maazxkqIAAAAA:cBn5y1eKnJUh7Tl4GVsw9Hqv984qwQ3_b8XvSM_wM3U2zp_-363uPINWJADEmMt-8ZjPzA1yaoE

* Three situations
  * CA: the system cannot suffer from network partitioning (single server)
  * AP: in case of partitioning, the system sacrifices consistency (overbooking)
  * CP: in case of partitioning, the system sacrifices availability (bookings prevented)
* Theorem interpretation is not trivial
  * Asymmetric properties: consistency is sacrificed to favor speed at all times, not just when partitioning happens
  * Different application requirements  different algorithms handle these properties more strictly/loosely

# Consistency in NoSQL: relaxing CAP

* Consider two users that want to book the same room when a network partition happens
* __CP__: no one can book (_A is sacrificed_)
  * Not the best solution
* __AP__: both can book (_C is sacrificed_)
  * Possible overbooking: writing conflict to handle
* _ __caP__ _: only one can book
  * The other will se the room available but cannot book it
* _This is admissible only in certain scenarios_
  * Finance? Blogs? E-commerce?
* It’s important to understand:
  * _What is the tolerance to obsolete reads_
  * _How large can the inconsistency window be_

---

Gestione del conflitto in scrittura:
Last one wins (vince l’ultimo che arriva)
Segnalazione all’utente del conflitto
Quorum

# Consistency in NoSQL: PACELC

* Evolution of the CAP theorem (less known, but more precise)
  * if (_P_ _artition_) then {  _A_ _vaialbility_ _ or _C_ _onsistency_? }
  * _E_ _lse_  {  _L_ _atency _ or _C_ _onsistency_? }
* Different behavior in case or in absence of partitioning
  * PA: in case of partitioning, the system sacrifices consistency (overbooking)
  * PC: in case of partitioning, the system sacrifices availability (bookings prevented)
  * EL: otherwise, the system sacrifices consistency in favor of speed
  * EC: otherwise, the system sacrifices speed in favor of consistency
* Four situations:
  * PA EL: system focused on speed and availability (main NoSQL philosophy)
  * PA EC: consistency sacrificed only when partitioning happens
  * PC EL: consistency enforced only when partitioning happens (e.g., Yahoo Sherpa)
  * PC EC: system focused on consistency (RDBMS)

---

http://dbmsmusings.blogspot.com/2010/04/problems-with-cap-and-yahoos-little.html

# Consistency in NoSQL: BASE

* The CAP theorem is often cited as a justification for the use of weaker consistency models, for example _ __BASE__ _
  * _Basically Available Soft-state services with Eventual consistency_
* _B_ _asic _ _A_ _vailability: _ the system should always be available
* _S_ _oft-state: _ it is acceptable for the system to be temporarily inconsistent
* _E_ _ventual consistency: _ eventually, the system becomes consistent
* ACID
  * Pessimistic approach (better safe than sorry)
* BASE
  * Optimistic approach (everything is going to be ok)
  * Higher throughput is better than enforcing consistency

# Consistency in NoSQL: summary

| Source | Cause | Effect | Solution |
|:-: |:-: |:-: |:-: |
| Replication(MS and P2P) | Write propagation delay between replicas is slow | Read conflicts | - Tolerate<br />- Read-your-writes<br />- Quorum |
| Replication (P2P) | Two write operations can be issued on different replicas | Write conflicts | - Last write wins<br />- Conflict prevention<br />- Conflict detection<br />- Quorum |
| Network partitioning | Inability to communicate with all replicas of a certain data | - Read conflicts<br />- Possibly write conflicts | - Relax CAP<br />- Prevent write conflicts<br />- Handle read conflict as above |
| No ACID transactions | - An update over multiple records fails mid-query<br />- Two updates over multiple records are interleaved | Unrecoverable inconsistency | - Each system provides its own mechanism to offer limited ACID-like transactions |
| Data de-normalization | The same data is repeated in different instances with different values | Inability to find the correct values | - Avoid denormalization if strong consistency is needed<br />- Data cleaning before analysis |

# One size does not fit all

To each application its own data model

# Key-Value: popular DBs

* __Redis__ (Data Structure server): [http://redis.io/](http://redis.io/)
  * Supports complex fields (list, set, ...) and operations on values (range, diff, ...)
* __Memcached DB: __ [http://memcached.org/](http://memcached.org/)
* __Riak__: [http://basho.com/riak/](http://basho.com/riak/)

# Key-Value: when to use

* Very simple use cases
  * Independent data (no need to model relationships)
  * The typical query is a simple lookup
  * Need super-fast performance
* Examples
  * __Session information__
    * Each web session is identified by its own sessionId: All related data can be stored with a PUT request and returned with a GET request
  * __User profiles, preferences__
    * Each user is uniquely identified (userId, username) and has her own preferences in terms of language, colors, timezone, products, etc. – _data that fits well within an aggregate_
  * __Shopping cart, chat services__
    * Each e-commerce websites associates a shopping cart to a user; it can be stored as _an aggregate identified by the user ID_

---

1 RDBMS would be overkill


# Key-Value: real use cases

* __Crawling of web pages__
  * The URL is the key, the whole page content (HTML, CSS, JS, images, ..)is the value
* __Twitter timeline__
  * The user ID is the key, the list of mostrecent tweets to be shown is the value
* __Amazon S3 (Simple Storage Service)__
  * A cloud-based file system service
  * Useful for personal backups, file sharing, website or apps publication
  * The more you store, the more you pay
    * Storage: approx. $0.03 per GB per month
    * Uploading files: approx. $0.005 per 1000 items
    * Downloading files: approx. $0.004 per 10,000 files* PLUS $0.09 per GB (first GB free)

![](imgs/slides89.png)

---

1 RDBMS would be overkill
https://www.infoq.com/presentations/Real-Time-Delivery-Twitter
http://highscalability.com/blog/2014/9/8/how-twitter-uses-redis-to-scale-105tb-ram-39mm-qps-10000-ins.html
https://www.quora.com/Why-is-Twitter-not-using-NoSQL

# Key-Value: when to avoid

* __Data with many relationships__
  * When relationships between data (in the same or in different collections) must be followed
  * Some systems offer limited link-walking mechanisms
* __Multi-record operations__
  * Because operations (mostly) involve one record at a time
* __Querying the data__
  * If it is necessary to query the values, not just the key
  * Few systems offer limited functionalities (e.g., Riak Search)

# Document: popular DBs

__MongoDB__: [http://www.mongodb.org](http://www.mongodb.org/)

__Couchbase: __ [http://www.couchbase.com](http://www.couchbase.com/)

__CouchDB__: [http://couchdb.apache.org](http://couchdb.apache.org/)

# Document: when to use

* Higher expressiveness
  * Store data according to a highly nested data model
  * Need to formulate complex queries on many fields
* Examples
  * __Event logs__
    * _Central repo to store event logs from many applications; _ shard on app name or event type
  * __CMS, blogging platforms__
    * _The absence of a predefined schema _ _fits well_ _ within content management systems (CMS) or website management applications, to handle comments, registrations and user profiles
  * __Web Analytics or Real-Time Analytics__
    * _The ability to update only specific fields _ enables fast update of analytical metrics
    * _Text indexing_ enables real-time sentiment analysis and social media monitoring
  * __E-commerce applications__
    * _Schema flexibility is often required _ to store products and orders, as well as to enable schema evolution without incurring into refactoring or migration costs

# Document: real use cases

* __Adversting__ __ services__
  * MongoDB was born as a system for banner ads
    * 24/7 availability and high performance
    * Complex rules to find the right banner based on user’s interests
    * Handle several kinds of ads and show detailed analytics
* __Internet of Things__
  * Real-time management of sensor-based data
  * Bosch uses MongoDB to capture data from cars (breaks, ABS, windscreen wiper, etc.) and aircrafts maintenance tools
    * Business rules are applied to warn the pilot when the breaking system pressure falls under a critical threshold, or the maintenance operator when the tool is used improperly
  * Technogym uses MongoDB to capture data from gym equipment

# Document: when to avoid

* __ACID transactions requirement__
  * If not for a few exceptions (e.g., RavenDB), document databases are not suited for cross-document atomicity
* __Queries on high-variety data__
  * _If the aggregate structure continuously evolves, queries must be constantly updated _ (and normalization clashes with the concept of aggregate)

# Wide column: popular DBs

__Cassandra__: [http://cassandra.apache.org](http://cassandra.apache.org/)

__HBase__: [https://hbase.apache.org](https://hbase.apache.org/)

__Google __ __BigTable__:  [https://cloud.google.com/bigtable](https://cloud.google.com/bigtable/)

# Wide column: when to use

* Compromise between expressiveness and simplicity
  * Limited (but some) requirements in terms of data model
  * Limited (but some) requirements in terms of querying records
* Examples
  * __Event logs; CMS, blogging platforms__
    * Similarly to document databases, _different applications may use different columns_
  * __Sparse matrixes__
    * While an RDBMS would store _null _ values, a wide column _stores only the columns for which a value is specified_
  * __GIS applications__
    * Pieces of a map (tiles) can be stored as _couples of latitude and longitude_

# Wide column: real use cases

* __Google applications__
  * BigTable is the DB used by Google for most of its applications, including Search, Analytics, Maps and Gmail
* __User profiles and preferences__
  * Spotify uses Cassandra to store metadata about users, artists, songs, playlists, etc.
* __Manhattan__
  * After using Cassandra, Twitter ha developed its own proprietary NoSQL system to support most of its services

---

Netflix: 12M trans/sec. Ebay, >100TB. IoT

https://labs.spotify.com/2015/01/09/personalization-at-spotify-using-cassandra/

https://academy.datastax.com/resources/ds220-data-modeling?unit=use-cases-use-case-introduction


# Wide column: when to avoid

* __Same as for document model__
  * ACID transactions requirement
  * Queries on high-variety data
* __Need for full query expressiveness__
  * Joins are highly discouraged
  * Limited support for filters and group bys

---

Prototipazioni: nelle prima fasi di progetto, i pattern delle query possono cambiare frequentemente, con la conseguenza di dover riprogettare le famiglie di colonne. In Cassandra, the cost may be higher for query change as compared to schema change.


# Graph: popular DBs

__Neo4J__: [http://neo4j.com](http://neo4j.com/)

__TigerGraph__: [https://www.tigergraph.com/](https://www.tigergraph.com/)

# Graph: when to use

* __Interlinked data__
  * _Social networks_ are one of the most typical use case of graph databases (e.g., to store friendships or work relationships); _every relationship-centric domain is a good one_
* __Routing and location-based services__
  * Applications working on the _TSP (Travelling Salesman Problem)_ problem
  * Location-based application that, for instance, recommend the best restaurant nearby; in this case, _relationships model the distance between node_
* __Recommendation applications, fraud-detection__
  * Systems recommending «the products bought by your friends», or «the products bought by those who bought your same products»
  * When relationships model behaviors, outlier detection may be useful to identify frauds

# Graph: real use cases

* __Relationships analysis__
  * Finding common friends (e.g., friend-of-a-friend) in a social network
  * Identifying clusters of phone calls that identify a criminal network
  * Analyzing flows of money to identifying money recycling patterns or credit card theft
  * Main users: law firms, police, intelligence agencies
    * [https://neo4j.com/use-cases/fraud-detection/](https://neo4j.com/use-cases/fraud-detection/)
  * Useful for text analysis as well (Natural Language Processing)
* __Inference__
  * Creating rules that define new knowledge based on existing patterns (e.g., transitive relationships, trust mechanisms)

---

https://developer.ibm.com/dwblog/2017/detecting-complex-fraud-real-time-graph-databases/

# Graph: when to avoid

* __Data-intensive applications__
  * Traversing the graph is trivial, but _analyzing the whole graph can be expensive_
  * There exist framework for distributed graph analysis (e.g., Apache Giraph), but they do not rely on a graph DB

# Polyglot persistence

* _Different databases are designed to solve _ _differen_ _t problems_
* _Using a single DBMS to handle everything ..._
  * Operational data
  * Temporary session information
  * Graph traversing
  * OLAP analyses
  * ...
* _... usually lead to inefficient solutions_
* Each activity has its own requirements (availability, consistency, fault tolerance, etc.)

![](imgs/slides90.jpg)

---

Termine derivato da "programmazione poliglotta"

# Traditional approach

The _one-size-fits-all_ solution

![](imgs/slides91.png)

---

The session, shopping cart, or order data do not need the same properties of availability, consistency, or backup requirements. Does session management storage need the same rigorous backup/recovery strategy as the e-commerce orders data? Does the session management storage need more availability of an instance of database engine to write/read session data?

In 2006, Neal Ford coined the term polyglot programming, to express the idea that applications should be written in a mix of languages to take advantage of the fact that different languages are suitable for tackling different problems. Complex applications combine different types of problems, so picking the right language for each job may be more productive than trying to fit all aspects into a single language.


# Polyglot data management

The _one-size-fits-all_ solution

Replaced by the _polyglot _ solution

![](imgs/slides92.png)

---

A key-value data store could be used to store the shopping cart data before the order is confirmed by the customer and also store the session data so that the RDBMS is not used for this transient data. Key-value stores make sense here since the shopping cart is usually accessed by user ID and, once confirmed and paid by the customer, can be saved in the RDBMS. Similarly, session data is keyed by the session ID. If we need to recommend products to customers when they place products into their shopping carts—for example, “ your friends also bought these products” or “ your friends bought these accessories for this product”—then introducing a graph data store in the mix becomes relevant.

Even using specialized relational databases for different purposes, such as data warehousing appliances or analytics appliances within the same application, can be viewed as polyglot persistence



# Service-oriented polyglot data management

* Each DB should be "embedded" within services, which offer API services to enable data access and manipulation
  * Several NoSQL systems (e.g., Riak, Neo4J) already provide REST APIs

![](imgs/slides93.png)

# Supporting existing technologies

If the current solution cannot be changed, NoSQL systems can still support the existing ones

![](imgs/slides94.png)

---

While doing this, we need to update the indexed data as the data in the application database changes. The process of updating the data can be real-time or batch, as long as we ensure that the application can deal with stale data in the index/search engine. The event sourcing (“ Event Sourcing,” p. 142) pattern can be used to update the index.

# Beyond NoSQL

* NewSQL systems
  * Combine the benefits from both relational and NoSQL worlds
  * Ensure scalability without compromising consistency, but by __compromising some availability__
* Extended RDBMSs
  * KV implementable as a table with two fields: a string key, and a blob value
  * Cypher query language on top of a relational implementation of a graph
  * Hstore data type in PostgreSQL for wide-column-like implementation
  * __Scalabilty__ __ issue remains__
* Multi-model NoSQL DBMSs
  * ArangoDB, OrientDB
  * __Support all NoSQL data models, but not the relational one__
* Database-as-a-service
  * All cloud providers offer storage services supporting all data models

# -- newsection --

# Cloud computing

# 

![](imgs/slides95.png)

[https://xkcd.com/1444/](https://xkcd.com/1444/)

# Reference scenario

* The big-data cube
  * Volume: small to big
  * Variety: structure to unstructured
  * Velocity: pull to push

Meijer, Erik. "Your mouse is a database."  _Communications of the ACM_ 55.5 (2012): 66-73.

* __Variety__
  * __Structured__
    * Relational tuples with FK/PK relationships
  * __Unstructured__
    * Key-value
    * Columnar
    * Document-based
    * Graph
    * ...

![](imgs/slides96.png)

![](imgs/slides97.png)

[https://www.datamation.com/big-data/structured-vs-unstructured-data/](https://www.datamation.com/big-data/structured-vs-unstructured-data/) (accessed 2022-08-01)

* __Velocity__ (latency)
  * __High__: clients synchronously pulling data from sources
  * __Low__: sources asynchronously pushing data to clients
* __Velocity__ (speed; dual to latency)
  * __High__: processing in real-time (milliseconds) or near-real time (minutes)
  * __Low__: processing can take hours

![](imgs/slides98.png)

* __Acceleration__
  * Velocity is not constant, data comes in bursts
  * Take Twitter as an example
    * Hashtags can become hugely popular and appear hundreds of times in just seconds
    * ... or slow down to one tag an hour
  * Your system must be able to efficiently handle the peak as well as the lows

![](imgs/slides99.png)

![](imgs/slides100.jpg)

![](imgs/slides101.jpg)

![](imgs/slides102.png)

[https://www.domo.com/learn/data-never-sleeps-9](https://www.domo.com/learn/data-never-sleeps-9)

The Netflix scenario

[https://www.domo.com/learn/data-never-sleeps-9](https://www.domo.com/learn/data-never-sleeps-9)

Collecting data

Processing data

  * _ __Scheduled Batch__ _
    * Large volume of data processed on a regular scheduled basis
    * Velocity is very predictable
  * _ __Periodic__ _:
    * Data processed at irregular times (e.g., after collecting a certain ---large--- amount of data)
    * Velocity is less predictable
  * _ __Near real-time__ _
    * Streaming data processed in small individual batches collected and processed within minutes
    * Velocity is a huge concern
  * _ __Real-time__ _
    * Streaming data collected and processed in very small individual batches within milliseconds
    * Velocity is the paramount concern

  * _ __Batch and periodic__ _
    * Once data has been collected, processing can be done in a controlled environment
    * There is time to plan for the appropriate resources
  * _ __Near real-time and real-time__ _
    * Collection of the data leads to an immediate need for processing
    * Depending on the complexity of the processing (cleansing, scrubbing, curation), this can slow down the velocity of the solution significantly
    * Plan accordingly

* Plus other Vs
  * __Veracity__: __ __ data trustworthiness/quality
  * __Value__: ability to extract meaningful information
  * ...
* Our focus
  * (Un)Structured big-data batch
  * (Un)Structured big-data streams
* __Goal__: keep in mind the cube to
* categorize the services

* Scenario 1
  * My business has a set of 15 JSON data files that are each about 2.5 GB in size.
  * They are placed on a file server once an hour, and they must be ingested as soon as they arrive in this location.
  * Data must be combined with all transactions from financial dashboard for this same period, then compared to the recommendations from marketing engine
  * All data is fully cleansed.
  * The results from this time period must be made available to decision makers by 10 minutes after the hour in the form of financial dashboards.

_Which Vs are involved?_

* Scenario 1
  * My business has a set of 15 JSON data files that are each about 2.5 GB in size.
  * They are placed on a file server once an hour, and they must be ingested as soon as they arrive in this location.
  * Data must be combined with all transactions from financial dashboard for this same period, then compared to the recommendations from marketing engine
  * All data is fully cleansed.
  * The results from this time period must be made available to decision makers by 10 minutes after the hour in the form of financial dashboards.

* Which Vs are involved?
  * _Volume_ This scenario describes huge JSON files to be combined with transactional data and marketing data.
  * _Velocity_ "Wait - now hurry up!" Wait to collect data for a full hour and then produce meaningful results in 10 minutes _(is it batch or stream processing?)_
  * _Variety_ three data source types: log files, transactional data, and recommendation information
  * _Value_ populate dashboards that are used by decision makers as soon as they are made available. The value is reached because it requires an understanding of what the organization is trying to accomplish

* Scenario 2
  * My business compiles data generated by hundreds of corporations.
  * This data is delivered to us in very large files, transactional updates, and even data streams.
  * The data must be cleansed and prepared to ensure that rogue inputs do not skew the results.
  * Knowing the data source for each record is vital to the work we do.
  * A large portion of the data gathered is irrelevant to our analysis, so this data must be eliminated.
  * The final requirement is that all data must be combined and loaded into our data warehouse, where it will be analyzed.

_Which Vs are involved?_

* Scenario 2
  * My business compiles data generated by hundreds of corporations.
  * This data is delivered to us in very large files, transactional updates, and even data streams.
  * The data must be cleansed and prepared to ensure that rogue inputs do not skew the results.
  * Knowing the data source for each record is vital to the work we do.
  * A large portion of the data gathered is irrelevant to our analysis, so this data must be eliminated.
  * The final requirement is that all data must be combined and loaded into our data warehouse, where it will be analyzed.

* Which Vs are involved?
  * _Volume_ The data is delivered in very large files, transactional updates, and even in data streams
  * _Variety_ The business will need to combine the data from all three sources into a single data warehouse.
  * _Veracity_ The data is known to be suspect. The data must be cleansed and prepared to ensure that rogue inputs do not skew the results. Knowing the data source for each record is vital to the work we do.

# Data-driven companies

* _Data-driven company _ refers to companies where decisions and processes are supported by data
  * Decisions are based on quantitative rather than qualitative knowledge
  * Processes & Knowledge are an asset of the company and are not lost if managers change
  * The gap between a data-driven decision and a good decision is a good manager
* Adopting a data-driven mindset goes far beyond adopting a business intelligence solution and entails:
  * _Create a data culture_
  * _Change the mindset of managers_
  * _Change processes_
  * _Improve the quality of all the data_

# Why going cloud?

* _Digitalization_ is a journey that involves three main dimensions
  * Moving from A to B is a multi-year process made of intermediate goals
  * Each of which must be _feasible_
    * Solves a company pain and brings value
    * Can be accomplished in a limited time range (typically less than one year)
    * Costs must be economically related to gains

Are processes extensively digitalized and produces reliable data?

_Technological_ _infrastructure_

Do we have the right persons to drive the project and exploit the results?

_Data quality _

_& quantity_

Is the technogical infrastructure appropriate to support data collection and analysis?

* __Cloud computing__ (National Institute of Standards and Technology)
  * _“A model for enabling _ _ubiquitous, convenient, on-demand _ _network access to a _ _shared pool_ _ of configurable computing resources (e.g., networks, servers, storage, services) that can be rapidly provisioned and released with _ _minimal management effort _ _or service provider interaction.”_
  * On-demand self-service (consume services when you want)
  * Broad network access (consume services from anywhere)
  * Resource pooling (infrastructure, virtual platforms, and applications)
  * Rapid elasticity (enable horizontal scalability)
  * Measured service (pay for the service you consume as you consume)
* __Digital transformation __ involves the __cloud__ to create/change business flows
  * Often involves changing the company culture to adapt to this new way of doing business
  * One of the end goal is to meet ever-changing business and market demand

* Goal: adjusts capacity to have predictable performance at the lowest cost
* __Scalability__ that is not possible on premises
  * Scale from one to thousands of servers
* __Elasticity__
  * Automatically scale resources in response to run-time conditions
  * Adapt to changes in workload by turning on/off resources to match the necessary capacity
  * Core justification for the cloud adoption

* Hardware scalability
  * No longer think about rack space, switches, and power supplies, etc.
* Grow storage from GBs to PBs
  * 1PB: one hundred 10TB Enterprise Capacity 3.5 HDD hard drives

![](imgs/slides103.jpg)

[https://blog.seagate.com/business/linus-tech-tips-want-petabyte-system/](https://blog.seagate.com/business/linus-tech-tips-want-petabyte-system/)

* __Resource pooling__
  * Enable _cost-sharing_ , a resource to serve different consumers
  * Resources are dynamically reassigned according to demands
  * Based on _virtualization_ , _ _ running multiple virtual instances on top of a physical computer system
  * Economy of scale for physical resources
* __Reliability__
  * Built to handle failures
  * Fault-tolerant or highly available

* Worldwide __deployment__
  * Deploy applications as close to customers as possible
    * E.g., to reduce network latency
  * Improve data locality
  * Compliant to privacy regulations (e.g., GDPR)
* Measured __quality of service__
  * Services leverage a quantitative qualitative metering capability making pay-as-you-go (or pay-per-use) billing and validation of the service quality available

* Service __integration__
  * Do not reinvent the wheel, eliminate repetitive tasks
    * Use services that solve common problems (e.g., load balancing, queuing)
  * Abstract and automatically adapt the architecture to requirements
    * E.g., create (test) environments on demand
* _Integration_ and _abstraction_ are drivers of change
  * From _databases_ to _data platforms_
  * From _on-premises_ to _serverless_ architectures
  * From _custom_ to _standardized_ data pipelines

# Is cloud a silver bullet?

![](imgs/slides104.png)

[https://www.reuters.com/article/us-france-ovh-fire-idUSKBN2B20NU](https://www.reuters.com/article/us-france-ovh-fire-idUSKBN2B20NU)

* Cloud computing is the outsourcing of a company’s hardware and software architecture
  * Which are the risks and issues?

---

Google has a long track record on clean energy: in 2007, Google became the first major company to become carbon neutral. And in 2017, Google became the first company of our size to match 100% of its electricity consumption with renewable energy. Today, Google Cloud is the only major cloud provider to purchase enough renewable energy to cover our entire operations, and over the years, we’ve purchased more wind and solar power than any other corporation in history. 
But wind and solar power don’t work in all places at all times. Though we buy enough renewable energy on average to match our data centers’ electricity consumption, that average is an annual average. Thus, for a particular data center, at any given time we may have too much renewable power, or too little. When we have too much, we feed it into the local grid so someone else can consume it. When we have too little, we draw power from the local grid, and that power may not be renewable.


![](imgs/slides105.png)

![](imgs/slides106.png)

Left: Mytton, David. "Data centre water consumption."  _npj_ _ Clean Water_ 4.1 (2021): 1-6.Right: [https://cloud.google.com/blog/topics/inside-google-cloud/announcing-round-the-clock-clean-energy-for-cloud](https://cloud.google.com/blog/topics/inside-google-cloud/announcing-round-the-clock-clean-energy-for-cloud) (accessed 2022-08-01)

---

Google has a long track record on clean energy: in 2007, Google became the first major company to become carbon neutral. And in 2017, Google became the first company of our size to match 100% of its electricity consumption with renewable energy. Today, Google Cloud is the only major cloud provider to purchase enough renewable energy to cover our entire operations, and over the years, we’ve purchased more wind and solar power than any other corporation in history. 
But wind and solar power don’t work in all places at all times. Though we buy enough renewable energy on average to match our data centers’ electricity consumption, that average is an annual average. Thus, for a particular data center, at any given time we may have too much renewable power, or too little. When we have too much, we feed it into the local grid so someone else can consume it. When we have too little, we draw power from the local grid, and that power may not be renewable.


# 

![](imgs/slides107.png)

[https://xkcd.com/908/](https://xkcd.com/908/)

# Cloud computing: types of cloud

* There are different types of cloud
  * __Public__: accessible to anyone willing to pay (e.g., Microsoft, AWS, Google)
  * __Private__: accessible by individuals within an institution
    * In public cloud, any resources that you are not using can be used by other
    * Users share the costs
    * Cost-sharing disappears in private clouds
  * __Hybrid__: a mix of the previous

![](imgs/slides108.png)

* Cloud services are hosted in separate geographic areas
  * Locations are composed of __regions__ and __availability zones__
* Region (e.g., us-east-1)
  * Is an independent geographical area that groups data centers
  * Has availability zones
* Availability zones in a region
  * A data center
  * Connected through low-latency links
  * Resources are usually replicated across zones but not regions

![](imgs/slides109.png)

[https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html)

# Cloud computing: principal vendors

![](imgs/slides110.png)

* Gartner Magic Quadrant
  * Understanding the technology providers to consider for an investment
  * __Leaders__ execute well and are well positioned for tomorrow
  * __Visionaries__ understand where the market is going but do not yet execute well
  * __Niche Players__ focus successfully on a small segment, or are unfocused and do not out-innovate or outperform others
  * __Challengers__ execute well but do not demonstrate an understanding of market direction
  * Focusing on leaders isn’t always the best
    * A niche player may support needs better than a market leader. It depends on how the provider aligns with business goals

[https://www.gartner.com/en/research/methodologies/magic-quadrants-research](https://www.gartner.com/en/research/methodologies/magic-quadrants-research)

# Cloud computing: deployment models

* On a cloud architecture, you can rely on _serverless_ or _managed _ services
* _Serverless_
  * Standalone independent services built for a specific purpose and integrated by cloud service provider
  * No visibility into the machines
    * There are still servers in serverless, but they are abstracted away
    * No server management, do not have to manage any servers or scale them
    * E.g., when you run a query on [BigQuery](https://cloud.google.com/blog/products/bigquery/separation-of-storage-and-compute-in-bigquery) you do not know how many machines were used
  * Pay for what your application uses, usually per request or per usage
* _(Fully) Managed_
  * Visibility and control of machines
    * You can choose the number of machines that are being used to run your application
  * Do not have to set up any machines, the management and backup are taken care for you
  * Pay for machine runtime, however long you run the machines and resources that your application uses

[https://cloud.google.com/blog/topics/developers-practitioners/serverless-vs-fully-managed-whats-difference](https://cloud.google.com/blog/topics/developers-practitioners/serverless-vs-fully-managed-whats-difference) (accessed 2020-08-01)

* Understanding architectures is paramount to successful systems
  * Good architectures help to scale
  * Poor architectures cause issues that necessitate a costly rewrite
* __XaaS__ __ (anything as a service)__
  * A collective term that refers to the delivery of anything as a service
  * It encompasses the products, tools and technologies that vendors deliver to users

![](imgs/slides111.png)

* __On-premises__
  * Provisioning servers is time-consuming
    * A non-trivial environment is hard to set up
  * Require dedicated operations people
  * Often a distraction from strategic tasks

* __Infrastructure as a service (IaaS)__
  * A computing infrastructure provisioned and managed over the internet (e.g., AWS EC2)
  * Avoid expense/complexity of buying/managing physical servers/data-centers
  * IaaS overcomes issues on-premises
  * Possibly requires to manage many environments

* __Platform as a Service (PaaS)__
  * A development and deployment environment in the cloud (e.g., AWS Elastic Beanstalk)
  * Support complete application life-cycle: building, testing, deploying, etc.
  * Avoid expense/complexity of managing licenses and application infrastructure

* __PaaS__ and __containers__ are potential solutions to inconsistent infrastructures
* PaaS provides a platform for users to run their software
  * Developers write software targeting features/capabilities of the platform
* Containerization isolates an application with its own environment
  * Lightweight alternative to full virtualization
  * Containers are isolated but need to be deployed to (public/private) server
  * Excellent solution when dependencies are in play
  * Housekeeping challenges and complexities

* _Containers_ and _virtual machines _ are packaged computing environments
* _Containers_
  * On top of physical server and its host OS
  * Share the host OS kernel
  * Shared components are read-only
  * “Light”, take seconds to start
* _Virtual machines_
  * Emulate a hardware/software system
  * On top of a hypervisor (VM monitor)

![](imgs/slides112.jpg)

* __Function as a Service (__ __FaaS__ __)__
  * A coding environment, cloud provider provisions platform to run the code (e.g., AWS Lambda)
  * Infrastructure provisioning and management are invisible to the developer

* Principles of FaaS architectures
  * FaaS is based on a serverless approach, use a compute service to execute code on demand
  * Every function could be considered as a standalone service
  * Write single-purpose stateless functions
* Functions react to events
  * Design push-based, event-driven pipelines
  * Create thicker, more powerful front ends
  * Embrace third-party services (e.g., security)
* FaaS is not a silver bullet
  * Not appropriate for latency-sensitive applications
  * Strict specific service-level agreements
  * Migration costs
  * Vendor lock-in can be an issue

* __Software as a service (SaaS)__
  * An application environment
  * Access cloud-based apps over the Internet (e.g., email, Microsoft Office 365, Github)

# 

![](imgs/slides113.png)

[https://xkcd.com/1084/](https://xkcd.com/1084/)

# -- newsection --

# From data lake to data warehouse

---

https://catalog.us-east-1.prod.workshops.aws/workshops/ea7ddf16-5e0a-4ec7-b54e-5cadf3028b78/en-US

# Context: Soil moisture monitoring

![](imgs/slides114.jpg)

* Optimizing soil moisture is crucial for watering and crop performance [1]
  * _ __GOAL__ _: build an expert system to save water while improving fruit quality (i.e., provide a recommendation of the optimal amount of water)
  * _Soils _ have different water retention
  * _Watering systems _ have different behaviors (e.g., drippers and sprinklers)
  * _Plants _ have different water demand (e.g., Kiwi [2] vs Grapes)
  * _Sensors_ produce different measurements with different precisions

![](imgs/slides115.jpg)

![](imgs/slides116.jpg)

![](imgs/slides117.jpg)

![](imgs/slides118.jpg)

[1] Turkeltaub et al., Real-time monitoring of nitrate transport in the deep vadose zone under a crop field–implications for groundwater protection, Hydrology and Earth System Sciences 20 (8) (2016) 3099–3108.[2] M. Judd, et al., Water use by sheltered kiwifruit under advective conditions, New Zealand journal of agricultural research 29 (1) (1986) 83–92.

* (Example) Scenarios of digital transformation in agriculture
* Scenario \#1
  * The farmer/technician controls the watering system based only on the experience
  * No digital data/KPIs/automation
* Scenario \#2
  * The control of the watering system is refined by observing sensor data
  * Sensor data is digitalized, no KPIs/automatic
* Scenario \#3
  * Sensor data feeds a decision support system that, knowing how to optimize KPIs, controls the watering system

![](imgs/slides119.png)

* (Example) Scenarios of digital transformation in agriculture
* Scenario \#1
  * The farmer/technician controls the watering system based only on the experience
  * No digital data/KPIs/automation
* Scenario \#2
  * The control of the watering system is refined by observing sensor data
  * Sensor data is digitalized, no KPIs/automatic
* Scenario \#3
  * Sensor data feeds a decision support system that, knowing how to optimize KPIs, controls the watering system

![](imgs/slides120.png)

Artificial intelligence (AI) is intelligence demonstrated by machines. AI research has been defined as the field of study of intelligent agents, which refers to any system that perceives its environment and takes actions that maximize its chance of achieving its goals.

* We need to understand how the soil behaves
* _Simulate_ [1, 2] the soil behavior according to physical models [3]
  * However, a _fine tuning _ is required
  * We need to _know/parametrize everything_
    * Soil (e.g., retention curve, hysteresis [4])
    * Plant (e.g., roots, LAI)
    * Weather conditions (temperature, humidity, wind, precipitations)
    * Watering system (e.g., capacity, distance between drippers)
* Tuning can take months (of human interactions)!
  * Need to collect samples from the field... if parameters are incorrect, trace back
  * Need to implement/code all these features into the simulator [1, 2]
  * Hyper-parameter tuning with machine learning can help, but it is not a silver bullet

[1] Šimunek, J., et al. "HYDRUS: Model use, calibration, and validation." Transactions of the ASABE 55.4 (2012): 1263-1274.[2] Bittelli, Marco, et al. Soil physics with Python: transport in the soil-plant-atmosphere system. OUP Oxford, 2015.[3] Van Genuchten, M. Th. "A closed‐form equation for predicting the hydraulic conductivity of unsaturated soils." Soil science society of America journal 44.5 (1980): 892-898.[4] Pham, Hung Q., Delwyn G. Fredlund, and S. Lee Barbour. "A study of hysteresis models for soil-water characteristic curves." Canadian Geotechnical Journal 42.6 (2005): 1548-1568.

* But... we have sensors!                  [1]                                      [2]                                          [3]
  * These settings are too coarse to monitor soil moisture with precision
  * They require many sensors

![](imgs/slides121.png)

![](imgs/slides122.png)

![](imgs/slides123.png)

[1] Koyuncu, Hakan, et al. "Construction of 3D soil moisture maps in agricultural fields by using wireless sensor communication." Gazi University Journal of Science 34.1 (2021): 84-98.[2] Zheng, Zhong, et al. "Spatial estimation of soil moisture and salinity with neural kriging." International Conference on Computer and Computing Technologies in Agriculture. Springer, Boston, MA, 2008.[3] Fersch, Benjamin, et al. "Synergies for soil moisture retrieval across scales from airborne polarimetric SAR, cosmic ray neutron roving, and an in situ sensor network." Water Resources Research 54.11 (2018): 9364-9383.

# Reference scenario

* We consider an orchard where
  * _Kiwi plants _ are aligned along _rows_
  * Each row has many _ drippers_ (e.g., 1 every meter)
  * Drippers can water a _limited soil volume_

![](imgs/slides124.jpg)

Francia, Matteo, et al. "Multi-sensor profiling for precision soil-moisture monitoring." Computers and Electronics in Agriculture 197 (2022): 106924.

* We consider an orchard where
  * _Kiwi plants _ are aligned along _rows_
  * Each row has many _ drippers_ (e.g., 1 every meter)
  * Drippers can water a _limited soil volume_

![](imgs/slides125.png)

Francia, Matteo, et al. "Multi-sensor profiling for precision soil-moisture monitoring." Computers and Electronics in Agriculture 197 (2022): 106924.

# Sensor layouts and symmetry assumptions

* When the watered volume is symmetric along the row, a _2D grid of sensors _ (left) is sufficient to represent the entire soil volume
* When relevant moisture variations take place along the row too, a _3D grid of sensors_ (right) is required
  * E.g., too sparse drippers
  * E.g., non-homogeneous suction of the roots

![](imgs/slides126.png)

![](imgs/slides127.png)

Francia, Matteo, et al. "Multi-sensor profiling for precision soil-moisture monitoring." Computers and Electronics in Agriculture 197 (2022): 106924.

# Reference scenario

![](imgs/slides128.png)

* (a) Soil moisture is a continuum
* (b) Sensors return a discretized representation of soil moisture
  * The monitoring accuracy changes
  * depending on the _sensor_ _layout_

![](imgs/slides129.png)

![](imgs/slides130.png)

![](imgs/slides131.png)

Francia, Matteo, et al. "Multi-sensor profiling for precision soil-moisture monitoring." Computers and Electronics in Agriculture 197 (2022): 106924.

![](imgs/slides132.png)

![](imgs/slides133.jpg)

![](imgs/slides134.png)

![](imgs/slides135.png)

![](imgs/slides136.png)

Francia, Matteo, et al. "Multi-sensor profiling for precision soil-moisture monitoring." Computers and Electronics in Agriculture 197 (2022): 106924.

# In action

![](imgs/slides137.png)

Log in AWS Academy [https://awsacademy.instructure.com](https://awsacademy.instructure.com/)

In AWS, start the lab (it takes 5-10 minutes)

Download the Notebook from Virtuale

Upload the Notebook to Sagemaker (not in COLAB!)

# Data lake: AWS S3

* AWS Simple Storage Service (S3)
  * A _serverless_ object storage service offering industry-leading scalability, data availability, security, and performance.
  * Customers of all sizes and industries can store and protect any amount of data for virtually any use case, such as data lakes

![](imgs/slides138.png)

Last access 2022-08

# Data exploration: AWS SageMaker

* Amazon SageMaker
  * Fully _managed_ service that provides machine learning (ML) capabilities for data scientists and developers to prepare, build, train, and deploy high-quality ML models efficiently

![](imgs/slides139.png)

Last access 2022-08

# ETL: AWS Glue

* AWS Glue
  * A serverless data integration service to discover and prepare data for analytics
  * Provide capabilities for data integration so that you can start analyzing your data and putting it to use in minutes
  * Provide both visual and code-based interfaces to make data integration easier
  * Users can easily find and access data using the AWS Glue Data Catalog

![](imgs/slides140.png)

![](imgs/slides141.png)

![](imgs/slides142.png)

Last access 2022-08

![](imgs/slides143.png)

![](imgs/slides144.png)

Last access 2022-08

![](imgs/slides145.png)

![](imgs/slides146.png)

![](imgs/slides147.png)

![](imgs/slides148.png)

![](imgs/slides149.png)

Last access 2022-08

![](imgs/slides150.png)

![](imgs/slides151.png)

![](imgs/slides152.png)

![](imgs/slides153.png)

![](imgs/slides154.png)

Last access 2022-08

![](imgs/slides155.png)

![](imgs/slides156.png)

![](imgs/slides157.png)

![](imgs/slides158.png)

![](imgs/slides159.png)

Last access 2022-08

![](imgs/slides160.png)

![](imgs/slides161.png)

![](imgs/slides162.png)

![](imgs/slides163.png)

_select_ date_format(timestamp, 'yyyy-MM-dd HH') _as_ hour,        date_format(timestamp, 'yyyy') _as_ year,       date_format(timestamp, 'yyyy-MM') _as_ month,       date_format(timestamp, 'yyyy-MM-dd') _as_ date,       concat('(', xx, ', ', yy, ')') _as_ sensor,       xx _as_ dist, yy _as_ depth, value, timestamp _from_ (    _select_ from_unixtime(_int_ (timestamp / 3600) * 3600) _as_ timestamp,            xx, yy, _avg_ (value) _as_ value _from_ myDataSource _ group by _ xx, yy, _int_ (timestamp / 3600) * 3600)

![](imgs/slides164.png)

![](imgs/slides165.png)

![](imgs/slides166.png)

![](imgs/slides167.png)

![](imgs/slides168.png)

![](imgs/slides169.png)

Last access 2022-08

![](imgs/slides170.png)

![](imgs/slides171.png)

Last access 2022-08

# DWH: AWS RDS

* Amazon Relational Database Service (Amazon RDS)
  * A collection of managed services that makes it simple to set up, operate, and scale relational databases in the cloud

Last access 2022-08

![](imgs/slides172.png)

![](imgs/slides173.png)

Last access 2022-08

![](imgs/slides174.png)

![](imgs/slides175.png)

![](imgs/slides176.png)

![](imgs/slides177.png)

Last access 2022-08

![](imgs/slides178.png)

![](imgs/slides179.png)

Last access 2022-08

# Designing the DWH

# -- newsection --

# Data pipelines on cloud (Storage)

# Data pipeline

* Data pipeline
  * _"A _ _sequence_ _ of operations to transform and consume raw data"_

![](imgs/slides180.png)

[https://xkcd.com/2054/](https://xkcd.com/2054/)

Quemy, Alexandre. "Data Pipeline Selection and Optimization."  _DOLAP_ . 2019.

* The pyramid abstracts tons of techniques, algorithms, etc.
* To provide them as services, architecting data pipelines on cloud requires
  * Standardization (of common services)
  * Integration
  * Orchestration
  * Accessibility through simple APIs
* Let us look to data pipelines on different cloud services providers

# Data pipeline - AWS

* Three main categories
  * Ingest
    * Gateway, DataSync (batch)
    * Kinesis, SNS, SQS (stream)
  * Transform and store
    * S3 and Glacier (storage)
    * Glue (ETL)
  * Serve and consume
    * EMR (Hadoop-like cluster)
    * Athena (serverless query service to analyze data in Amazon S3)
    * (Many) Machine learning services

![](imgs/slides181.png)

[https://console.aws.amazon.com/console](https://console.aws.amazon.com/console)

# Data pipeline - Google cloud

* Three main categories
  * Ingest
    * Transfer service (batch)
    * Pub/Sub (stream)
  * Analyze
    * Dataproc (batch)
    * Dataflow (stream)
    * Cloud storage (storage)
    * Machine learning services
  * Serve
    * BigQuery (query service)

![](imgs/slides182.png)

# A tentative organization

Real-time processing and analytics

Operational metadata

Batch processing and analytics

Slow storage (data lake)

ETL tools overlay

* We have services
  * To transform data
  * To support the transformation
* The (DIKW) pyramid abstracts many techniques and algorithms
  * Standardization
  * Integration
  * Orchestration
  * Accessibility through APIs

Supporting services

Serve (deciding)

BI tools (e.g., Tableau)

Analytics (analyzing/process)

Networking, etc.

Machine learning

Ingestion (acquiring/collect)

# Data pipeline

* DIKW hierarchy
  * Layers representing structural relationships between data, information, knowledge, and wisdom

![](imgs/slides183.png)

![](imgs/slides184.jpg)

Ackoff, Russell L. "From data to wisdom." Journal of applied systems analysis 16.1 (1989): 3-9.

# A tentative organization

* This is not a sharp taxonomy
* Ingestion vs Analytics
  * Data streams are used for ingestion
  * ... and (event) processing

Supporting services

Serve (deciding)

BI tools (e.g., Tableau)

Analytics (analyzing)

Networking, etc.

Machine learning

Ingestion (acquiring)

* This is not a sharp taxonomy
* Storage vs Serving
  * Databases are storage
  * ... with processing capability
  * ... and with serving capability

Supporting services

Serve (deciding)

BI tools (e.g., Tableau)

Analytics (analyzing)

Networking, etc.

Machine learning

Ingestion (acquiring)

# 

Supporting services

Serve (deciding)

BI tools (e.g., Tableau)

Analytics (analyzing)

Networking, etc.

Machine learning

Ingestion (acquiring)

# Storage

* __Goal__: persisting data
* Which storage do we choose?
  * __Storage model __ (or data model) ~= variety
    * How data are organized/accessed in a storage system
      * Structured vs unstructured
      * Data access model (key-value, column, etc.)
  * Access __frequency__
  * __Analyses __ to be performed

# Storage models

![](imgs/slides185.png)

Mansouri, Yaser, Adel Nadjaran Toosi, and Rajkumar Buyya. "Data storage management in cloud environments: Taxonomy, survey, and future directions." ACM Computing Surveys (CSUR) 50.6 (2017): 1-51.

# Storage models (AWS)

* Data structure: structured
* Data abstraction: database
* Data access model: relational
* __Relational__
  * Store data with predefined schemas and relationships between them
  * Support ACID transactions
  * Maintain referential integrity

![](imgs/slides186.png)

[https://aws.amazon.com/products/databases/](https://aws.amazon.com/products/databases/)

* Data structure: semi/unstructured
* Data abstraction: database
* Data access model: *
  * __Key/value: __ store and retrieve large volumes of data
  * __Document: __ store semi-structured data as JSON-like documents
  * __Wide column:__ use tables but unlike a relational database, columns can vary from row to row in the same table
  * __Graph: __ navigate and query relationships between highly connected datasets
  * __... and more__

![](imgs/slides187.png)

[https://aws.amazon.com/products/databases/](https://aws.amazon.com/products/databases/)

# Storage models (Google Cloud)

![](imgs/slides188.png)

![](imgs/slides189.png)

[https://cloud.google.com/products/databases](https://cloud.google.com/products/databases)

# Storage models (AWS)

* Data structure: unstructured
* Data abstraction: file (or database)
* Data access model: key-value
* __File system__ (EFS), __object storage__ (S3) (or __DB K-V__ ; e.g., DynamoDB)
  * Handle unstructured data
  * ... organized as files (or blob)
  * ... accessed using a key-value
* Differ in the supported features
  * E.g., maximum item size (DynamoDB: 400KB, S3: 5TB)
  * E.g., indexes, querying mechanisms, latency, etc.

# AWS S3

* Simple Storage Service (S3)
  * Serverless storage, save data as __objects__ within __buckets__ 
  * An __object__ is composed of a file and any metadata that describes that file (e.g.,  __object key__)
  *  __Buckets__ are logical containers for objects
    * You can have one or more buckets in your account
    * Control access for each bucket individually
    * Choose the geographical region where Amazon S3 will store the bucket and its contents
* Benefits
  * Unified data architecture
    * Build a multi-tenant environment, where many users can bring their own data
    * Improve both cost and data governance over traditional solutions
  * Decoupling of storage from compute and data processing
    * You can cost-effectively store all data types in their native formats
    * Then, launch transformations as you need

# Storage: access frequency (AWS)

* 24 storage (AWS S3) __classes__
  * __Standard__: general purpose
  * __Infrequent__ (rapid) __access__
  * __One Zone-IA__: lower-cost option for infrequently accessed data that do not require high availability and resilience
  * __Glacier__: low-cost storage class for data archiving, three retrieval options that range from a few minutes to hours
  * __Deep Glacier__: long-term retention for data accessed once or twice in a year. E.g., retain data sets for 10 years or longer
  * __Intelligent-Tiering__: move objects between access tiers when access patterns change

![](imgs/slides190.png)

[https://aws.amazon.com/s3/storage-classes/](https://aws.amazon.com/s3/storage-classes/)

* __Lifecycle__ configuration
  * A set of rules that define actions that Amazon S3 applies to a group of objects
* Two types of actions:
  * __Transition: __ when objects transition to another storage class. E.g., archive objects to the S3 Glacier storage class one year after creating them
  * __Expiration__: when objects expire. Amazon S3 deletes expired objects on your behalf

![](imgs/slides191.png)

[https://docs.aws.amazon.com/AmazonS3/latest/userguide/object-lifecycle-mgmt.html](https://docs.aws.amazon.com/AmazonS3/latest/userguide/object-lifecycle-mgmt.html)

# Storage: access frequency (Google Cloud)

![](imgs/slides192.png)

![](imgs/slides193.png)

[https://cloud.google.com/blog/products/storage-data-transfer/archive-storage-class-for-coldest-data-now-available](https://cloud.google.com/blog/products/storage-data-transfer/archive-storage-class-for-coldest-data-now-available)

# Organizing the data lake

* Having consistent principles on how to organize your data is important
  * To build standardized pipelines with the same design with regard to where read/write data
  * Standardization makes it easier to manage your pipelines at scale
  * Helps data users search for data in the storage and understand exactly to find what they need
  * Decoupling storage from processing

* Landing area (LA)
  * Save _raw data_ from ingestion
  * Transient, data is not stored for long term
* Staging area (SA)
  * Raw data goes through a set of common transformations: ensuring _basic quality_ and making sure it _conforms to existing schemas_ for this data source and then data is saved into SA
* Archive area (A)
  * After saving into SA, raw data from LA should be _copied into the archive_ to reprocess any given batch of data by simply copying it from AA into LA
  * Useful for debugging and testing

* Production area (PA)
  * Apply the business logic to data from SA
* Pass-through job
  * Copy data from SA to PA and then into DWH without applying any business logic
  * Optional, but having a data set in the data warehouse and PA that is an exact replica can be helpful when debugging any issues with the business logic
* Cloud data warehouse (DWH)
* Failed area (FA)
  * You need to be able to deal with all kinds of errors and failures
  * There might be bugs in the pipeline code, cloud resources may fail

| Area | Permissions | Tier |
|:-: |:-: |:-: |
| Landing | Ingestion applications can write<br />Scheduled pipelines can readData consumers can’t access | Hot |
| Staging | Scheduled pipelines can read/write<br />Selected data consumers can read | Hot |
| Production | Scheduled pipelines can read/writeSelected data consumers can read | Hot |
| Archive | Scheduled pipelines can writeDedicated data reprocessing pipelines can read  | Cold or archive |
| Failed | Scheduled pipelines can writeDedicated data reprocessing pipelines can readData consumers don’t have access | Hot |

* Use folders to organize data inside areas into a logical structure
  * _Namespace_
    * Logically group multiple pipelines together.
  * _Pipeline name_
    * Each data pipeline should have a name that reflects its purpose. For example
      * A pipeline that takes data from the LA, applies common processing steps, and saves data into SA
      * You will also have one for archiving data into AA
  * _Data source name_
    * Ingestion layer will assign a name to each data source you bring into the platform
  * _BatchId_
    * Unique identifier for any batch of data that is saved into LA
    * E.g., Since only ingestion can write to LA, it is its responsibility to generate this identifier
    * A common choice for this type of an identifier is a Universally Unique Identifier (UUID)
* Different areas will have slightly different folder structures
  * /landing/ETL/sales_oracle_ingest/customers/01DFTFX89YDFAXREPJTR94

However, alternative organizations are available

> "A data lake is a central repository system for storage, processing, and analysis of raw data, in which the data is __kept in its original format __ and is processed to be queried only when needed. It can store a __varied amount of formats __ in big data ecosystems, from unstructured, semi-structured, to structured data sources."
>
> Couto et al., 2019 ​

# Data Lakehouse

* Combine the key benefits of data lakes and data warehouses
  * Low-cost storage in an open format accessible by a variety of systems from the former
  * Powerful management and optimization features from the latter
    * ACID transactions, data versioning, auditing, indexing, caching, and query optimization.
* Key question: can we combine these benefits in an effective way?
  * Direct access means that they __give up some aspects of data independence__ , which has been a cornerstone of relational DBMS design
  * __Lakehouses__ __ are an especially good fit for cloud environments with separate compute and storage__: different computing applications can run on-demand on separate computing nodes (e.g., a GPU cluster for ML) while directly accessing the same storage data

# Data Independence

  * Data independence can be explained using the three-schema architecture
  * Data independence: modify the schema at one level of the database system without altering the schema at the next higher level

![](imgs/slides194.png)

# Data Lakehouse

* __1__ __st__ __generation systems__: data warehousing started with helping business leaders get analytical insights
  * Data in these warehouses would be written with _schema-on-write_ , which ensured that the data model was optimized for downstream BI consumption
  * Several challenges
    * They typically coupled compute and storage into an on-premises appliance
      * This forced enterprises to provision and pay for the peak of user load and data under management, very costly
    * More and more datasets were completely unstructured, which DWHs could not store and query at all

Armbrust, Michael, et al. "Lakehouse: a new generation of open platforms that unify data warehousing and advanced analytics."  _CIDR_ . 2021.

---

https://dl.acm.org/doi/fullHtml/10.1145/3524284

* __2__ __nd__ __generation__: offloading all the raw data into data lakes
  * The data lake is _schema-on-read_ and stores any data at low cost, but on the other hand, punted the problem of data quality and governance
  * In this architecture, a small subset of data in the lake would later be ETLed to a downstream data warehouse
  * The use of open formats also made data lake data directly accessible to a wide range of other analytics engines, such as machine learning systems
  * From 2015 onwards, cloud data lakes, such as S3, ADLS and GCS, started replacing HDFS
    * Superior durability (often >10 nines), geo-replication, and most importantly, extremely low cost

![](imgs/slides195.png)

* While the cloud data lake and warehouse architecture is ostensibly cheap, a two-tier architecture is highly complex for users
  * Data is first ETLed into lakes, and then again ELTed into warehouses
  * Enterprise use cases now include advanced analytics such as machine learning, for which neither data lakes nor warehouses are ideal
  * (Some) main problems:
    * __Reliability__ . Keeping the data lake and warehouse consistent is difficult and costly
    * Data __staleness__ . The data in the warehouse is stale compared to that of the data lake, with new data frequently taking days to load
    * __Limited support for advanced analytics__ . Businesses want to ask predictive questions using their warehousing data, e.g., “which customers should I offer discounts to?” None of the leading machine learning systems directly work well on top of warehouses
      * Process large datasets using complex non-SQL code

# Dataset Search for Data Discovery, Augmentation, and Explanation

* Is there a real need for many unstructured and integrated dataset?
  * Recent years have seen an explosion in our ability to collect and catalog immense amounts of data about our environment, society, and populace
  * Governments, and organizations are increasingly making structured data available on the Web and in various repositories and data lakes
  * __This opportunity is often missed due to a central technical barrier__: it is currently nearly impossible for domain experts to weed through the vast amount of available information to discover datasets that are needed for their specific application

Juliana Freire, keynote @ EDBT 2023

# Data Lakehouse

* Main features
  * __Store data in a low-cost object store__ using a standard file format such as Apache Parquet
  * __Implement a transactional metadata layer__ on top of the object store that defines which objects are part of a table version
  * __Implement management features __ within the metadata layer
* Challenges:
  * The metadata layer is insufficient to achieve good SQL performance
    * __Data warehouses use several techniques to get state-of-the-art performance__
      * Storing hot data on fast devices such as SSDs, maintaining statistics, building efficient indexes, etc.
    * __In a Lakehouse it is not possible to change the format__ , but it is possible to implement other optimizations that leave the data files unchanged

# Delta Lake

* __Challenges__:
  * Most __cloud object stores are merely key-value stores__ , with no cross-key consistency
  * __Multi-object updates are not atomic__ , there is no isolation between queries
    * If a query needs to update multiple objects in the table readers will see partial updates as the query updates each object individually
  * For large tables with millions of objects, __metadata operations are expensive__
    * The latency of cloud object stores is so much higher that these data skipping checks can take longer than the actual query

Armbrust, Michael, et al. "Delta lake: high-performance ACID table storage over cloud object stores." Proceedings of the VLDB Endowment 13.12 (2020): 3411-3424.

* Delta Lake uses a __transaction log __ that is compacted __into Apache Parquet __ for significantly faster metadata operations for large tabular datasets
  * E.g., quickly search billions of table partitions for those relevant to a query
  * The log is stored in the __delta_log__ subdirectory within the table
  * It contains
    * Sequence of JSON objects with increasing, zero-padded numerical IDs to store the log records
    * Occasional checkpoints for specific log objects that summarize the log up to that point

![](imgs/slides196.png)

* Each log record object (e.g., 000003.json) contains an array of actions to apply to the previous version of the table to generate the next one
* Examples of actions are:
  * Change Metadata
  * Add or Remove Files
* It is necessary to compress the log periodically into checkpoints
  * Checkpoints store all the non-redundant actions in the table’s log up to a certain log record ID, in Parquet format
  * Some sets of actions are redundant and can be removed
  * Read the _last_checkpoint object in the table’s log directory, if it exists, to obtain a recent checkpoint ID

* Example of a write transaction
  * Transaction will read the data at table version r (if needed) and attempt to write log record r+1
  * Read data at table version r, if required combine previous checkpoint and further log records
  * Write any new data objects that the transaction aims to add to the table into new files in the correct data directories, generating the object names using GUIDs.
    * This step can happen in parallel
    * At the end, these objects are ready to be referenced in a new log record.
  * Attempt to write the transaction’s log record into the r+1 .json log object, if no other client has written this object
  * __This step needs to be atomic__ . If the step fails, the transaction can be retried; depending on the query’s semantics (optimistic concurrency)
  * Optionally, write a new .parquet checkpoint for log record r+1
* Creating the r+1 .json record, needs to be atomic: only 1 client should succeed. Not all large-scale storage systems have an atomic put operation
  * Google Cloud Storage and Azure Blob Store support atomic put-if-absent operations
  * HDFS, we use atomic renames to rename a temporary file to the target name
  * Amazon S3 need ad-hoc protocols

# Lakehouse

* (SQL) Format-independent optimizations are
  * __Caching__: When using a transactional metadata layer such as Delta Lake, it is safe for a Lakehouse system to cache files from the cloud object store on faster storage devices such as SSDs and RAM on the processing nodes
  * __Auxiliary data__: maintain column min-max statistics for each data file in the table within the same Parquet file used to store the transaction log, which enables data skipping optimizations when the base data is clustered by particular columns
  * __Data layout__:
    * Record ordering: which records are clustered together and hence easiest to read together, e.g. ordering records using individual dimensions or space-filling curves such as Z-order
    * Compression strategies differently for various groups of records, or other strategies
* Offer a declarative version of the DataFrame APIs which maps data preparation computations into Spark SQL query plans and can benefit from logical optimizations

# -- newsection --

# Data pipelines on cloud (Computing)

# 

Supporting services

Serve (deciding)

BI tools (e.g., Tableau)

Analytics (analyzing)

Networking, etc.

Machine learning

Ingestion (acquiring)

# Supporting data pipelines

* We can choose the XaaS configuration to build our pipelines
* IaaS
  * Outsource virtual machines to the cloud (AWS EC2)
  * (You) Manage technological and business challenges
* PaaS
  * Outsource the data ecosystem to the cloud (e.g., AWS EMR)
  * (You) Manage business challenges

![](imgs/slides197.png)

![](imgs/slides198.png)

[https://aws.amazon.com/ec2](https://aws.amazon.com/emr)[https://aws.amazon.com/emr](https://aws.amazon.com/emr)  (2022-11-15)

# Single instance: AWS EC2

* Amazon Elastic Compute Cloud
  * A web service that provides resizable compute capacity
  * Complete control of computing resources
    * Processor, storage, networking, OS, and purchase model
* The _ __instance type __ _ determines the hardware
  * Different compute and memory capabilities
* _ __Amazon Machine Image __ _ is a software template
  * The EC2 instance is used for creating the virtual server instance
  * The AMI is the EC2 virtual machines image
* Interact with EC2 instance as with any computer
  * You have complete control of your instances

![](imgs/slides199.png)

[https://aws.amazon.com/ec2/instance-types](https://aws.amazon.com/ec2/instance-types) [https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instances-and-amis.html](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instances-and-amis.html) [https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/compute-optimized-instances.html](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/compute-optimized-instances.html)

![](imgs/slides200.png)

![](imgs/slides201.png)

[https://aws.amazon.com/ec2/instance-types/](https://aws.amazon.com/ec2/instance-types/)

* AWS uses public-key cryptography to secure the login
* You can create one using the Amazon EC2 console
  * Open the Amazon EC2 console at [https://console.aws.amazon.com/ec2/](https://console.aws.amazon.com/ec2/)
  * In the navigation pane, choose `Key Pairs`
  * Choose `Create key pair`
  * For `Name`, enter a descriptive name for the key pair
  * For `File format`, choose the format in which to save the private key
    * OpenSSH, choose `pem` (` chmod 400 _ _my-key-_ _ _pair_ _ .pe m `)
    * PuTTY, choose `ppk`
  * Choose `Create key pair`
  * The private key file is automatically downloaded by your browser

# Cluster: AWS EMR

* Amazon EMR is a data platform based on the Hadoop stack
  * Apache Spark, Apache Hive, Apache HBase, etc.
  * You can run workloads on
    * Amazon EC2 instances
    * Amazon Elastic Kubernetes Service (EKS) clusters
* Example of workload
  * Upload input data into Amazon S3
  * EMR launches EC2 instances that you specified
  * EMR begins the execution while pulling the input data from S3 into the launched instances
  * Once the cluster is finished, EMR transfers output data to Amazon S3

# Motivation

* Amazon EMR (Elastic Map Reduce)
  * Provides a managed Hadoop framework
* Some features
  * Service integration
    * Automatically control EC2 instances
    * Transparently use S3 storage
  * Pricing:
    * Low Hourly Pricing
    * Amazon EC2 Spot Integration

[https://aws.amazon.com/emr](https://aws.amazon.com/emr)

# AWS EMR

Deploy Multiple Clusters

Provision as much capacity as you need

Add or remove capacity at any time

![](imgs/slides202.png)

![](imgs/slides203.png)

![](imgs/slides204.png)

![](imgs/slides205.png)

![](imgs/slides206.png)

![](imgs/slides207.png)

![](imgs/slides208.png)

![](imgs/slides209.png)

![](imgs/slides210.png)

![](imgs/slides211.png)

![](imgs/slides212.png)

![](imgs/slides213.png)

![](imgs/slides214.png)

![](imgs/slides215.png)

![](imgs/slides216.png)

![](imgs/slides217.png)

![](imgs/slides218.png)

![](imgs/slides219.png)

![](imgs/slides220.png)

![](imgs/slides221.png)

![](imgs/slides222.png)

![](imgs/slides223.png)

![](imgs/slides224.png)

![](imgs/slides225.png)

![](imgs/slides226.png)

![](imgs/slides227.png)

![](imgs/slides228.png)

![](imgs/slides229.png)

![](imgs/slides230.png)

Resize a Running Cluster

![](imgs/slides231.png)

![](imgs/slides232.png)

![](imgs/slides233.png)

![](imgs/slides234.png)

![](imgs/slides235.png)

![](imgs/slides236.png)

![](imgs/slides237.png)

![](imgs/slides238.png)

![](imgs/slides239.png)

![](imgs/slides240.png)

![](imgs/slides241.png)

![](imgs/slides242.png)

![](imgs/slides243.png)

![](imgs/slides244.png)

![](imgs/slides245.png)

![](imgs/slides246.png)

![](imgs/slides247.png)

![](imgs/slides248.png)

![](imgs/slides249.png)

![](imgs/slides250.png)

![](imgs/slides251.png)

![](imgs/slides252.png)

![](imgs/slides253.png)

![](imgs/slides254.png)

![](imgs/slides255.png)

![](imgs/slides256.png)

![](imgs/slides257.png)

![](imgs/slides258.png)

![](imgs/slides259.png)

![](imgs/slides260.png)

![](imgs/slides261.png)

![](imgs/slides262.png)

![](imgs/slides263.png)

![](imgs/slides264.png)

![](imgs/slides265.png)

* EMR cluster
* Master group controls the cluster
  * Coordinate the work distribution
  * Manage the cluster state
* Core groups
  * Core instances run Data Node daemons
* (Optional) Task instances

![](imgs/slides266.png)

![](imgs/slides267.png)

![](imgs/slides268.png)

![](imgs/slides269.png)

Amazon EMR Cluster

Master Instance Group

![](imgs/slides270.png)

![](imgs/slides271.png)

![](imgs/slides272.png)

![](imgs/slides273.png)

![](imgs/slides274.png)

![](imgs/slides275.png)

![](imgs/slides276.png)

![](imgs/slides277.png)

![](imgs/slides278.png)

![](imgs/slides279.png)

Task Instance Group

Core Instance Group

![](imgs/slides280.png)

![](imgs/slides281.png)

![](imgs/slides282.png)

![](imgs/slides283.png)

![](imgs/slides284.png)

![](imgs/slides285.png)

![](imgs/slides286.png)

![](imgs/slides287.png)

* The central component of Amazon EMR is the __cluster__
  * A collection of __Amazon Elastic Compute Cloud (Amazon EC2)__ instances
  * Each instance is called a __node__
* The __node type __ identifies the role within the cluster
  * __Master__ node coordinates the distribution of data and tasks among other nodes
    * Every cluster has (at least) a master node
    * Always active
  * __Core__ node runs tasks and store data in the Hadoop Distributed File System (HDFS)
    * Multi-node clusters have at least one core node
    * Always active, contains the data node daemon
  * __Task__ node only runs tasks
    * Task nodes are optional
    * Decoupling processing and storage, we lose data locality

* On-Demand Instance
  * Pay for compute capacity by the hour (minimum of 60 seconds)
  * No long-term commitments
* Spot Instance
  * Unused EC2 instance that is available for less than the on-demand price
  * Hourly price is called _spot price_
    * Adjusted based on long-term supply and demand for spot instances
  * Run the instance when capacity is available and price is below threshold
    * When data-center resources are low, spot instances are dropped
    * Mainly suitable for batch workloads

[https://aws.amazon.com/ec2/pricing/](https://aws.amazon.com/ec2/pricing/)

---

https://us-east-1.console.aws.amazon.com/ec2/v2/home?region=us-east-1#SpotInstances:


* Spot Instance cost strategies
* _Capacity-optimized strategy_
  * Allocated instances into the most available pools
  * Look at real-time capacity data, predict which are the most available
  * Works well for workloads such as big data and analytics
  * Works well when we have high cost of interruption
* _Lowest-price strategy_
  * Allocates instances in pools with lowest price at time of fulfillment

# Creating the cluster

![](imgs/slides288.png)

![](imgs/slides289.png)

* Choose to launch __master__ , __core__ , or __task__ on Spot Instances
  * The __master__ node controls the cluster
    * When terminated, the cluster ends
    * Use _spot instances_ if you are running a cluster where sudden termination is acceptable
  * __Core __ nodes process data and store information using HDFS
    * When terminated, data is lost
    * Use _spot instances_ when partial HDFS data loss is tolerable
  * __Task __ nodes process data but do not hold persistent data in HDFS
    * When terminated, computational capacity is lost
    * The effect of spot instances on the cluster is "minimal"

[https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-plan-instances-guidelines.html](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-plan-instances-guidelines.html)

![](imgs/slides290.png)

* Amazon EMR provides two main file systems
  * __HDFS__ and __EMRFS__ , specify which file system to use by the prefix
  * hdfs://path (or just `path`)
    * HDFS is used by the master and core nodes
    * _AWS EBS volume storage is used for HDFS data_
    * Is fast, best used for caching the results produced by intermediate job-flow steps, _why?_
    * It’s ephemeral storage which is reclaimed when the cluster ends
  * s3://DOC-EXAMPLE-BUCKET1/path (EMRFS)
    * An implementation of the Hadoop file system atop Amazon S3
    * We can avoid EBS storage

[https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-plan-storage.html](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-plan-storage.html)

* Choose the frameworks and applications to install
* Data process
  * Submit jobs or queries directly to installed applications
  * Run steps in the cluster
* Submitting jobs
  * Connect to the master node over a secure connection
  * Access the interfaces and tools that are available on your cluster

![](imgs/slides291.png)

![](imgs/slides292.png)

![](imgs/slides293.png)

![](imgs/slides294.png)

Allows EMR to call other AWS Services such as EC2 on your behalf.

Provides access to other AWS services such as S3, DynamoDB from EC2 instances that are launched by EMR.

* Using CLI (command line interface)
* This is more pragmatic, but there are many options to explore
  * Let’s stick to AWS Console
  * [https://console.aws.amazon.com/elasticmapreduce/](https://console.aws.amazon.com/elasticmapreduce/)

* aws emr create-cluster \\
  * --name _ _"My First EMR Cluster" _ _ \\
  * --release-label _ _emr-5.32.0 _ _ \\
  * --applications Name=Spark \\
  * --ec2-attributes KeyName= _ _myEMRKeyPairName _ _ \\
  * --instance-type m5.xlarge \\
  * --instance-count 3 \\
  * --use-default-roles

Using CLI (command line interface)

aws emr create-cluster --auto-scaling-role EMR_AutoScaling_DefaultRole --termination-protected --applications Name=Hadoop Name=Hive Name=Hue Name=JupyterEnterpriseGateway Name=Spark --ebs-root-volume-size 10 --ec2-attributes '{"KeyName":"bigdata","InstanceProfile":"EMR_EC2_DefaultRole","SubnetId":"subnet-5fa2f912","EmrManagedSlaveSecurityGroup":"sg-07818b5690a50b3f1","EmrManagedMasterSecurityGroup":"sg-0e2f5550a2cb98f79"}' --service-role EMR_DefaultRole --enable-debugging --release-label emr-6.2.0 --log-uri 's3n://aws-logs-604905954159-us-east-1/elasticmapreduce/' --name 'BigData' --instance-groups '[{"InstanceCount":1,"BidPrice":"OnDemandPrice","EbsConfiguration":{"EbsBlockDeviceConfigs":[{"VolumeSpecification":{"SizeInGB":32,"VolumeType":"gp2"},"VolumesPerInstance":2}]},"InstanceGroupType":"MASTER","InstanceType":"m4.xlarge","Name":"Master - 1"},{"InstanceCount":1,"BidPrice":"OnDemandPrice","EbsConfiguration":{"EbsBlockDeviceConfigs":[{"VolumeSpecification":{"SizeInGB":32,"VolumeType":"gp2"},"VolumesPerInstance":2}]},"InstanceGroupType":"CORE","InstanceType":"m4.xlarge","Name":"Core - 2"}]' --scale-down-behavior TERMINATE_AT_TASK_COMPLETION --region us-east-1

# Cluster lifecycle

* Creating a cluster (it takes ~10 minutes)
  * A cluster cannot be stopped
  * It can only be terminated

![](imgs/slides295.png)

* STARTING: EMR provisions EC2 instances for each required instance
* BOOTSTRAPPING: EMR runs actions that you specify on each instance
  * E.g., install custom applications and perform customizations
* Amazon EMR installs the native applications
  * E.g., Hive, Hadoop, Spark, and so on
* RUNNING: a step for the cluster is currently being run
  * Cluster sequentially runs any steps that you specified when you created the cluster
* WAITING: after steps run successfully
* TERMINATING: after manual shut down
  * _Any data stored on the cluster is deleted_

* A __step__ is a user-defined unit of processing
  * E.g., one algorithm that manipulates the data
* Step states
  * PENDING: The step is waiting to be run
  * RUNNING: The step is currently running
  * COMPLETED: The step completed successfully
  * CANCELLED: The step was cancelled before running because an earlier step failed
  * FAILED: The step failed while running

# Running the cluster

![](imgs/slides296.png)

![](imgs/slides297.png)

# Running a notebook

![](imgs/slides298.png)

![](imgs/slides299.png)

![](imgs/slides300.png)

# Running a Spark Job

Connect using SSH

Install git

Clone & build the project

ssh -i ~/bigdata.pem [hadoop@ec2-54-242-176-32.compute-1.amazonaws.com](mailto:hadoop@ec2-54-242-176-32.compute-1.amazonaws.com)

sudo yum install git -y

git clone [https://github.com/w4bo/spark-word-count.git](https://github.com/w4bo/spark-word-count.git)

cd spark-word-count

./gradlew

spark-submit --class it.unibo.big.WordCount build/libs/WordCount-all.jar s3://aws-bucket-bigdata2021/inferno.txt

# Other services: HUE

* Connecting to Hue
  * I.e., connecting to any HTTP interface hosted on the master node of a cluster
* To view the Hue web user interface
  * Set Up an SSH Tunnel to the Master Node Using Dynamic Port Forwarding
  * Type the following address in your browser to open the Hue web interface
    * [http://master-public-DNS:8888](http://master-public-dns:8888/)
    * Where master-public-DNS is the public DNS name of the master node
  * If you are the administrator logging in for the first time
    * Enter a username and password to create your Hue superuser account
    * Otherwise, type your username and password and select Create account

![](imgs/slides301.png)

# Set Up an SSH Tunnel

![](imgs/slides302.png)

![](imgs/slides303.png)

![](imgs/slides304.png)

# Connect to HUE

![](imgs/slides305.png)

![](imgs/slides306.png)

# Connect using SSH

![](imgs/slides307.png)

![](imgs/slides308.png)

# 

![](imgs/slides309.png)

# -- newsection --

# Cluster migration - Based on a true story​

# Migration

* Goals
  * Evaluating the costs for a cloud/on-premises data platform
  * Real-world case study
  * Fill in this table

| Cost | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware |? |? |
| Software |? |? |

# Case study

Business intelligence group

# Migration

Spatial Cube (PostGIS)

Reference architecture

![](imgs/slides310.png)

Mobile Interface

ODS (Hbase+PostGIS)

Integration processes

Loading processes

Notebook Interface

Data Lake (Hadoop)

Enrichment processes

Acquisition processes

_External sources_

![](imgs/slides311.png)

![](imgs/slides312.png)

![](imgs/slides313.png)

![](imgs/slides314.png)

![](imgs/slides315.png)

![](imgs/slides316.png)

Administrative

borders

Rural Land

register

Satelliteimages

On-the-field sensors

Reference architecture

![](imgs/slides317.png)

* Hardware
* Software
  * "Classic" Hadoop stack

* 8 CPUs (144 total)
  * - Intel(R) Core(TM) i7-8700 CPU @ 3.20GHz
* 32GB RAM (576GB total)
  * - 2 x 16GB DIMM DDR4 2666 MHz
* 12TB HDD Disk (216TB total)
  * - 3 x 4TB ST4000DM004-2CV1

![](imgs/slides318.png)

![](imgs/slides319.png)

![](imgs/slides320.png)

![](imgs/slides321.png)

![](imgs/slides322.png)

![](imgs/slides323.png)

![](imgs/slides324.png)

![](imgs/slides325.png)

![](imgs/slides326.png)

![](imgs/slides327.png)

![](imgs/slides328.png)

![](imgs/slides329.png)

![](imgs/slides330.png)

![](imgs/slides331.png)

![](imgs/slides332.png)

![](imgs/slides333.png)

![](imgs/slides334.png)

![](imgs/slides335.png)

![](imgs/slides336.png)

![](imgs/slides337.png)

lshw -short -C cpu

lshw -short -C memory

lshw -short -C disk

| SOLonprem | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware |? |? |
| Software |? |? |

* __Hardware cost__:?
  * Refer to [https://www.rect.coreto-europe.com/en/search.html?clearsearch=1](https://www.rect.coreto-europe.com/en/search.html?clearsearch=1)

# On-premises

| SOLonprem | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 10602€/year |? |
| Software |? |? |

* __Hardware cost __ _(up to Mar 05, 2021): _ 1767€ x 18 = 31806€
  * Amortization over 3 years (i.e., _10602€/year_)

![](imgs/slides338.png)

[https://www.rect.coreto-europe.com/en](https://www.rect.coreto-europe.com/en) (Accessed 2021-08-01)

| SOLonprem | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 10602€/year |? |
| Software |? |? |

__Software cost__:?

| SOLonprem | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 10602€/year |? |
| Software | 0€ |? |

* __Software cost__ _(up to 2020): 0€_
  * Free Cloudera Management System
  * No software licensing (for research purpose)

| SOLonprem | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 10602€/year |? |
| Software | 180000€/year |? |

* __Software cost __ _(up to Mar 05, 2021): 10000€/year x 18 = 180000€/year_
  * Cloudera is no more free, 10K€ per node
  * [https://www.cloudera.com/products/pricing.html\#private-cloud-services](https://www.cloudera.com/products/pricing.html#private-cloud-services)
  * [https://www.cloudera.com/products/pricing/product-features.html](https://www.cloudera.com/products/pricing/product-features.html)
  * No license for research purpose
* _“Houston we’ve had a problem!”_
  * We cannot update/extend the cluster anymore
  * What about migrating to the cloud? (we only consider AWS)

# Migration

* Moving a Hadoop cluster to the cloud (we only consider AWS)
  * AWS price calculator [https://calculator.aws/\#/estimate](https://calculator.aws/#/estimate)
* How do we start?
  * We have already defined the hardware and the software stack
  * Start with coarse tuning, identify the dominating costs first
    * Is it computing, storage, or processing?
  * Identify a suitable budget, implement, refine later
    * Wrong refinements can do a lot of damage

# On cloud v1

| SOLcloud1 | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 10602€/year |? |
| Software | 180000€/year |? |

* Migrating the cluster as-is:?
  * Hint: add 18 EC2 instances satisfying the hardware requirements

| SOLcloud1 | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 10602€/year | 162000$/year |
| Software | 180000€/year |? |

* SOLcloud1 migrating the cluster as-is: _13500$/month = 162000$/year_
  * 18 EC2 instances (t4g.2xlarge) with 12TB EBS storage each machine
  * Still, we have no software configuration
* Prices change over the year
  * In 2022, 162000$/year
  * In 2023, 146000$/year

![](imgs/slides339.png)

[https://calculator.aws/\#/estimate?id=7757afffccc3cafdcfdeb212b74623ef02ed5a36](https://calculator.aws/#/estimate?id=7757afffccc3cafdcfdeb212b74623ef02ed5a36)

# Migration

* Pay attention to the region
  * Different regions, different prices
  * Different regions, different services
  * Remember the GDPR and data locality

![](imgs/slides340.png)

* It makes no sense to move the cluster as-is
  * More machines ensure better (on-prem) scalability but higher costs
* How do we proceed with the migration?
  * We need minimum software requirements
  * Try to achieve the smallest migration impact
    * Find the most similar cloud-based solution to a Hadoop cluster
    * Rethink applications (later) when you got the know-how
  * Identify a suitable budget, implement, refine later
    * Wrong refinements can do a lot of damage

* __HDFS__
  * How much durability do we need?
    * HP0: three replicas (we stick to this)
    * HP1: decrease replicas for cold data
    * HP2: move cold data to glacier or delete id
    * ...
* __HBase__ has marginal effects on the pricing (100GB << 50TB)
  * For simplicity, we can omit it
* __Overall__: 50TB storage/year

![](imgs/slides341.png)

* Processing takes place each time that ESA provides a satellite image
  * Some days no images are available
  * Some days up to 10 images are available
  * Spark jobs are always executed with the same parameters
* __Image processing__
  * 4 machines, 2 cores, 10GB RAM at least
* __Weather processing__ is negligible

Image processing

4 Executors (2 cores and 10GB RAM each)

Driver (2 cores and 20GB RAM)

: 15m/core (2h total)

Weather processing

2 Executors (1 core and 500MB RAM each)

Driver (1 core and 1GB RAM)

: 0.5 m/core (1m total)

# On cloud v2

|  | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 2356€/year | 38000$/year |
| Software | 100000€/year |? |

* Assuming 1 Executor = 1 Machine
  * Compare 4 machines on-premises vs on cloud
* On-premises
  * 4 machines: 10602€/year / 18 machines x 4 machines = _2356€/year_
  * Cloudera requires at least 10 nodes: _100000€/year_
* AWS
  * 4 EC2 instances: 162000$/year / 18 machines x 4 machines = _36000$/year_
    * Plus the resources for master services = _2000$/year_
  * Problems
    * Still no software stack
    * A lot of storage cost
    * Machines are up-and-running even when no computation is necessary (just to persist data)

* AWS
  * Still, we have no software stack configuration
  * Which is the major cost?

* AWS
  * Still, we have no software stack configuration
  * Which is the major cost?

![](imgs/slides342.png)

![](imgs/slides343.png)

# Migration

S3 standard

S3 Infrequent Access

![](imgs/slides344.png)

![](imgs/slides345.png)

* _AWS Storage_
* HDFS on EC2
  * Heavy price
  * Machine must be always on to guarantee data persistency
  * Data locality
* S3
  * Much cheaper
  * Does not require machines for data storage
  * Data locality is lost

![](imgs/slides346.png)

![](imgs/slides347.png)

|  | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 2356€/year |? |
| Software | 100000€/year |? |

* Migrating cluster to EMR: _?_
* Given the software requirements, we need
  * 1 x Master Node (to manage the cluster)1 x Core node (with HDFS/EBS)
  * 4 x Task Nodes (to compute)

Image processing

4 Executors (2 cores and 10GB RAM each)

Driver (2 cores and 20GB RAM)

: 15m/core (2h total)

Weather processing

2 Executors (1 core and 500MB RAM each)

: 0.5 m/core (1m total)

Driver (1 core and 1GB RAM)

# On cloud v3

|  | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 2356€/year | 14710€/year |
| Software | 100000€/year |? |

* Migrating cluster to EMR: _14710€/year_
  * S3 Infrequent Access storage (50 TB per month): 640€
  * 1 x Master EMR nodes, EC2 (m4.xlarge), Utilization (75 h/month): 4.5€
    * 75 h/month = 15min/task x 10task/day x 30day/month / 60min/hour
  * 1 x Core EMR nodes, EC2 (m4.xlarge), Utilization (75 h/month): 4.5€
  * 4 x Task EMR nodes, EC2 (m4.4xlarge), Utilization (75 h/month): 72€
  * 4 x EC2 _on demand (task node): 174.83€_
    * Storage amount (30 GB)
    * Workload (Daily, Duration of peak: 0 Hr 15 Min)
    * Instance type (m4.xlarge)
  * 2 x EC2 on demand (master and core nodes): 330€
    * Storage amount (30 GB)
    * Instance type (m4.xlarge)

|  | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 2356€/year | 13445€/year |
| Software | 100000€/year |? |

* Migrating cluster to EMR: _13445€/year_
  * S3 Infrequent Access storage (50 TB per month): 640€
  * 1 x Master EMR nodes, EC2 (m4.xlarge), Utilization (75 h/month): 4.5€
    * 75 h/month = 15min/task x 10task/day x 30day/month / 60min/hour
  * 1 x Core EMR nodes, EC2 (m4.xlarge), Utilization (75 h/month): 4.5€
  * 4 x Task EMR nodes, EC2 (m4.4xlarge), Utilization (75 h/month): 72€
  * 4 x EC2 _spot (task node): 69.55€_
    * Storage amount (30 GB)
    * Workload (Daily, Duration of peak: 0 Hr 15 Min)
    * Instance type (m4.xlarge)
  * 2 x EC2 on demand (master and core nodes): 330€
    * Storage amount (30 GB)
    * Instance type (m4.xlarge)

 _[https://calculator.aws/\#/estimate?id=c3780b12bb43b593d05def5a1d5218d9764b8a65](https://calculator.aws/#/estimate?id=c3780b12bb43b593d05def5a1d5218d9764b8a65)_ 

# Migration

Summing up (cloud options)

| Machine uptime | Storage | Software | Feasible? | Cost per year |
|:-: |:-: |:-: |:-: |:-: |
| Constant | EC2 | Manual | YES: but high storage cost | ~36K€ |
| Constant | EC2 | EMR | YES: but high storage cost | ~37K€ |
| Constant | S3 | Manual | YES: but still manual provisioning | ~17K€ |
| Constant | S3 | EMR | YES | ~18K€ |
| Pay-per-use | EC2 | Manual | NO: pay-per-use + EC2 = Data unpersisted | - |
| Pay-per-use | EC2 | EMR | NO: pay-per-use + EC2 = Data unpersisted | - |
| Pay-per-use | S3 | Manual | ISH: repetitive manual provisioning | - |
| Pay-per-use | S3 | EMR | YES | ~14K€ |

* Summing up
  * We estimated the cluster costs
    * On-premises solution with 18 machines: no go
    * Cloud solution with 18 EC2 instances: no go
  * We reduced the solution based on software requirements
    * On-premises solution with 4 machines: no go
    * Cloud solution with 4 EC2 instances: no go, we miss the software configuration
  * We moved the cluster to AWS EMR + spot instances + S3 storage
* Can we do better?
  * Pick ad-hoc cloud services (AWS Lambda e AWS Batch)
  * ... to re-think the applications (food for thoughts)

# Case study

WeLASER

# The WeLASER project

* __Project description__
  * _The increased use of pesticides and _ _fertilisers_ _ damages the environment, destroys non-target plants and beneficial insects for the soil and harms human and animal health. Most seeds develop herbicide-resistant properties, rendering pesticides ineffective. Mechanical automatic systems that are studied as alternatives to pesticides deteriorate soil features, damage beneficial soil organisms and offer limited results for in-row weeding. The EU-funded WeLASER project will develop a non-chemical solution for weed management based on pioneering technology consisting of the application of lethal doses of energy on the weed meristems through a high-power laser source. An AI-vision system separates crops from weeds, identifying the weed meristems and pointing the laser at them. A smart controller based on IoT and cloud computing techniques coordinates the system, which is _ _transfered_ _ all over the field by an autonomous vehicle._

![](imgs/slides348.png)

[https://cordis.europa.eu/project/id/101000256](https://cordis.europa.eu/project/id/101000256) (accessed 2020-08-01)

* Which requirements do you foresee?
* Can we define a tentative (service) architecture for the WeLASER project?
* Assumptions
  * Do not consider the collection of weed/crop images & training/deploying of the CV algorithm

![](imgs/slides349.png)

[https://cordis.europa.eu/project/id/101000256](https://cordis.europa.eu/project/id/101000256) (accessed 2020-08-01)

# Data sources

[https://docs.google.com/spreadsheets/d/17zEr62CzyqeIy0vU-DcjEUoxf6bMd3ziLSSeIXvk4Lg/edit?usp=sharing](https://docs.google.com/spreadsheets/d/17zEr62CzyqeIy0vU-DcjEUoxf6bMd3ziLSSeIXvk4Lg/edit?usp=sharing)

# Workload

* Nothing special
  * Every night compute aggregated indexes on the collected data (2h/day)
* On-premises (HDFS cluster)
  * How many machines do we need?
  * With which resources?

# On-premises

|  | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 2900€/year |? |
| Software | 40000€/year |? |

* On-premises
  * How many machines do we need?
    * _4_: _1 master node_ + _3 HDFS data nodes_
  * With which resources?
    * Assuming a HDFS replication factor of 3, we need at least 1TB of disk overall (not that much)
    * Think bigger: at least 8 cores, 64GB RAM, 500GB SSD + 4TB HDD, no GPU
  * 8700€ / 3 years = 2900€

![](imgs/slides350.png)

![](imgs/slides351.png)

[https://www.rect.coreto-europe.com/en](https://www.rect.coreto-europe.com/en) (accessed 2022-09-01)[https://www.cloudera.com/products/pricing.html](https://www.cloudera.com/products/pricing.html) (accessed 2022-09-01)

# On cloud v1

|  | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 2900€/year | ~40000$/year |
| Software | 40000€/year |? |

* Moving the Hadoop cluster as IAAS
* EC2
  * Quantity (4), Pricing strategy (EC2 Instance Savings Plans 3 Year No Upfront), _Storage amount (4 TB), _ Instance type (r6g.2xlarge)
* EMR
  * Number of master EMR nodes (1), EC2 instance (r5.2xlarge), Utilization (100 %Utilized/Month) Number of core EMR nodes (3), EC2 instance (r5d.2xlarge), _Utilization (100 %Utilized/Month)_
* _MKS (KAFKA)_
  * Storage per Broker (10 GB), Number of Kafka broker nodes (3), Compute Family (m5.2xlarge)

![](imgs/slides352.png)

[https://calculator.aws/\#/estimate?id=05965ca7de23fd9e7d2ab2cd0175fe8c01822c9c](https://calculator.aws/#/estimate?id=05965ca7de23fd9e7d2ab2cd0175fe8c01822c9c) (accessed 2022-09-01)

# On cloud v2

|  | On-premises | On cloud |
|:-: |:-: |:-: |
| Hardware | 2900€/year | ~4000$/year |
| Software | 40000€/year |? |

* Moving the Hadoop cluster as PAAS
* EC2
  * Quantity (4), Pricing strategy (_On-Demand Instances_), Storage amount (30 GB), Instance type (r6g.2xlarge)
* EMR
  * Number of master EMR nodes (1), EC2 instance (r5.2xlarge), Utilization (2 Hours/Day) Number of core EMR nodes (3), EC2 instance (r5d.2xlarge), _Utilization (2 Hours/Day)_
* _S3_
  * Standard storage (60 GB per month)
* _Kinesis_
  * Days for data retention (1 days), Records (100 per second), Consumer Applications (3)

![](imgs/slides353.png)

[https://calculator.aws/\#/estimate?id=53f60ff0412a18877dc8e1274f7d9875aa3bf665](https://calculator.aws/#/estimate?id=53f60ff0412a18877dc8e1274f7d9875aa3bf665) (accessed 2022-09-01)

# Cost vs price

How would you evaluate the cost and the price?

* _Price_ is the amount a customer is willing to pay for a product or service
* _Cost_ is the expense incurred for creating a product or service
  * Hardware
  * Development
  * Maintenance
* _Profit_ is the difference between price paid and costs incurred is profit
  * If a customer pays $10 for a product that costs $6 to make and sell, the company earns $4

# -- newsection --

# Data pipelines on cloud (Streaming)

# 

Supporting services

Serve (deciding)

BI tools (e.g., Tableau)

Analytics (analyzing)

Networking, etc.

Machine learning

Ingestion (acquiring)

# Reference scenario: batch vs stream

# Batch vs. Streaming systems

* What is a bulk processing system?
  * High latency
  * Exact results
  * Process massive data at once
    * ... is this true?

* What is a streaming system?
  * Low latency
  * Approximate result
    * ... is this true?
  * Process data item by data item
    * ... is this true?

* What is a bulk processing system?
  * An engine capable to handle processing on __bounded__ datasets

* What is a streaming system?
  * An engine capable to handle processing on __unbounded__ datasets
  * Streaming is a superset of batch processing

Akidau, Tyler, Slava Chernyak, and Reuven Lax.  _Streaming systems: the what, where, when, and how of large-scale data processing_ . " O'Reilly Media, Inc.", 2018.

# Reference scenario: batch vs stream

|  | Batch data processing | Stream data processing |
|:-: |:-: |:-: |
| Data scope | Queries or processing over all or most of the data in the dataset | Queries or processing over data within a rolling time window, or on just the most recent data record |
| Data size | Large batches of data | Individual records or micro batches consisting of a few records |
| Latency | Minutes to hours | Seconds or milliseconds |
| Analysis | Complex analytics | Simple response functions, aggregates, and rolling metrics |

# Ingestion: batch

* __Goal__: moving data to the cloud
* Moving data to the cloud
  * _80TB_ of data to move,
  * _1Gbps_ connection to the internet
* How many _days_?
  * _80000GB_ / (_1Gbps / 8_) /  _60 / 60 / 24 _ ~= a week without internet

* Batch/Bulk: move data from on-premises storage
* Workflow
  * Receive shipment
  * Set up
  * Transfer data
  * Ship back (shipping carrier)

# Ingestion: batch (AWS)

* AWS Snowball
  * 50TB (North America only) and 80TB versions
  * Not rack-mountable
* Throughput
  * 1 Gbps or 10 Gbps using an RJ-45 connection
  * 10 Gbps using a fiber optic connection

![](imgs/slides354.png)

[https://aws.amazon.com/snowball/](https://aws.amazon.com/snowball/)

![](imgs/slides355.png)

# AWS Snowmobile

What if we have exabyte of data?

Value Metric

103 KB (kilobyte)

106 MB (megabyte)

109 GB (gigabyte)

1012 TB (terabyte)

1015 PB (petabyte)

1018 EB (exabyte)

1021 ZB (zettabyte)

1024 YB (yottabyte)

[https://youtu.be/8vQmTZTq7nw?t=45](https://youtu.be/8vQmTZTq7nw?t=45) (2022-11-14)

# Ingestion: stream

  * Data (often) flows in both directions, storage systems are both sources and destinations for data transformations
  * Two pipelines per application (data in/out)
    * Worst case (full connectivity): O(N2)

![](imgs/slides356.png)

Kreps, Jay.  _I heart logs: Event data, stream processing, and data integration_ . " O'Reilly Media, Inc.", 2014.

* __Stream__: real-time streaming data
* __Event__: anything that we can observe occurring at a particular point in time
* __Continuous streaming__
  * Illimited succession of individual events
  * Ordered by the point in time at which each event occurred
* __Publish/subscribe (pub/sub)__: a way of communicating messages
  * _Senders_ publish messages associated with one or more __topics__
  * _Receivers_ subscribe to specific topics, receive all messages with that topic
  * _Messages_ are events

![](imgs/slides357.jpg)

[https://www.manning.com/books/event-streams-in-action](https://www.manning.com/books/event-streams-in-action)

* Log
  * Append-only data structure
  * Each application only knows about the log, it ignores the details of the source
    * E.g., a data consumer is not concerned about whether the data came from a relational database or some application
* The log acts as a messaging system with durability guarantees and ordering semantics

![](imgs/slides358.png)

Kreps, Jay.  _I heart logs: Event data, stream processing, and data integration_ . " O'Reilly Media, Inc.", 2014.

* General idea:
  * Collect events from many source systems
  * Store them in a unified log
  * Enable applications to operate on these event streams
* __Unified log__
  * _Unified_ , _append-only_ , _ordered_ , _distributed_ log that allows the centralization of event streams

![](imgs/slides359.jpg)

* __Unified__: a single log in a company with applications sending/reading events
  * Log serves as central data backbone
    * It can contain many distinct continuous streams of events
    * Not all events are sent to the same event stream
* __Append-only__: new events are appended to the unified log
  * Existing events are never updated in place
    * If read the event \#10, never look at events 1 through 10 again
  * Events are automatically deleted from the unified log when they age
    * E.g., automatically remove events after 7 days

* __Distributed__: the unified log lives across a cluster of machines
  * Optionally divide events into shards (i.e., partitions)Still, the log is unified since we have a single (conceptual) log
* Distribution ensures
  * Scalability: work with streams larger than the capacity of single machines
  * Durability: replicate all events within the cluster to overcome data loss
  * Using a log as a universal integration mechanism is never going to be more than an elegant fantasy if we can’t build a log that is fast, cheap, and scalable

![](imgs/slides360.jpg)

* __Ordered__: events in a shard have a sequential IDs (unique in a shard)
  * Local ordering keeps things much simpler than global ordering
  * Applications maintain their own cursor for each shard

![](imgs/slides361.jpg)

Lamport, Leslie. "Time, clocks, and the ordering of events in a distributed system."  _Concurrency: the Works of Leslie _ _Lamport_ . 2019. 179-196.

* Two types of processing
  * __Single-event:__ a single event produces zero or more events
    * Validating “Does this event contain all the required fields?”
    * Enriching “Where is this IP address located?”
    * Filtering “Is this error critical?”
  * __Multiple-event:__ multiple events collectively produce zero or more events
    * Aggregating, functions such as minimum, maximum, sum
    * Pattern matching, looking for patterns or co-occurrence
    * Reordering events based on a sort key

![](imgs/slides362.png)

* Why not communicating directly using messaging protocols?
* A log enables
  * Multi-subscriber: each data item is available to any processor that wants it
  * Order: maintained in the processing done by each consumer of data
  * Buffering and isolation to the individual processes
    * E.g., a that processor produces faster than its downstream consumer can keep up
  * Reprocessing, maintaining state, etc.
* Indeed, logs are common:
  * MapReduce workflows use files to checkpoint and share their intermediate results
  * SQL processing pipelines create intermediate or temporary tables

# Ingestion: stream (AWS)

* Amazon Kinesis Data Streams
  * Created and provisioned by shard
    * Each shard provides 1 MBps and 1000 data puts per second
  * A data record consists of
    * User-supplied partition key to balance records across shards
    * Incremental sequence number added by the shard
    * A data blob
  * Consumers get records by shard
    * Records are sorted by partition key and sequence number
    * Ordering is not guaranteed across shards
  * Records are retained for 7 days at maximum

![](imgs/slides363.png)

[https://docs.aws.amazon.com/streams/latest/dev/key-concepts.html](https://docs.aws.amazon.com/streams/latest/dev/key-concepts.html)

* Re-sharding (i.e., scaling)
  * Split a shard into two, or merge two shards
  * Users must scale shards up and down manually
    * Monitor usage with Amazon CloudWatch and modify scale as needed
  * Avoid shard management by using Kinesis Data Firehose
* Kinesis is a regional service, with streams scoped to specific regions
  * All ingested data must travel to the region in which the stream is defined
* Costs
  * Priced by shard hour, data volume, and data retention period
  * Pay for resources you provision (even if not used)

[https://aws.amazon.com/cloudwatch/](https://aws.amazon.com/cloudwatch/)[https://aws.amazon.com/kinesis/data-firehose](https://aws.amazon.com/kinesis/data-firehose)

# Ingestion: stream

| Feature | AWS Kinesis | Google Pub/Sub |
|:-: |:-: |:-: |
| Unit of deployment | Stream | Topic |
| Unit of provisioning | Shard | N/A (fully managed) |
| Data unit | Record | Message |
| Data producer/destination | Producer/Consumer | Publisher/Subscriber |
| Data partitioning | User-supplied partition key | N/A (fully managed) |
| Retention period | Up to 7 days | Up to 7 days |
| Pricing | Per shard-hour, PUT payload units,<br />and optional data retention | Message ingestion and delivery,<br />and optional message retention |

# 

Supporting services

Serve (deciding)

BI tools (e.g., Tableau)

Analytics (analyzing)

Networking, etc.

Machine learning

Ingestion (acquiring)

# Serverless computing/processing

* AWS Lambda: compose code functions in a loose orchestration
  * Build modular back-end systems
  * Event-driven and push-based pipelines
* With Lambda, you are responsible only for your code (Lambda function)
  * Lambda manages the compute fleet that offers a balance of memory and CPU
  * Lambda performs operational and administrative activities on your behalf
    * Provisioning capacity, monitoring fleet health, applying security patches, etc.

![](imgs/slides364.png)

# Serverless computing (AWS Lambda)

* AWS Lambda
  * A Lambda function is a granular service
  * The Lambda runtime invokes a lambda function multiple times in parallel
  * Compute service that executes code written in JavaScript/Python/C\#/Java
    * Elastic Compute Cloud (EC2) servers run the code (e.g., a Linux server)
  * A function is `code + configuration + dependencies`
    * Source code (JARs or DLLs) is zipped up and deployed to a container
  * Invocation supports push/pull events

![](imgs/slides365.png)

# Serverless computing (FaaS)

* FaaS: write single-purpose stateless functions
  * Keep the single responsibility principle in mind
  * A function that does just one thing is more testable and robust
  * A function with a well-defined interface is also more likely to be reused
  * Code should be created in a stateless style
    * Statelessness allows scalability
    * Local resources or processes will not survive along sessions
  * Functions that terminate sooner are cheaper
    * E.g., pricing is based on \#requests, execution time, and allocated memory

# Patterns for data pipelines

* Patterns are architectural solutions to problems in software design
  * A (design) pattern is a general, best-practice reusable solution to a commonly occurring problem within a given context in software design
  * It is a template for how to solve a problem in many different situations
* Patterns for serverless data pipelines
    * Command pattern
    * Messaging pattern
    * Priority queue pattern
    * Pipes and filters pattern

![](imgs/slides366.jpg)

[https://www.manning.com/books/aws-lambda-in-action](https://www.manning.com/books/aws-lambda-in-action)

# Command pattern

* Command pattern
  * A behavioral design pattern in which an object is used to encapsulate the information needed to perform an action or trigger an event
* Encapsulate a request as an object
  * Issue requests to objects without knowing anything about the operation being requested or the receiver

![](imgs/slides367.png)

[https://aws.amazon.com/api-gateway](https://aws.amazon.com/api-gateway)

# Pipes and filters pattern

* Decompose a complex processing task into a sequence of manageable services
  * Components designed to transform data are referred to as filters
  * Connectors that pass data between components are referred to as pipes

![](imgs/slides368.png)

# Messaging pattern

* Messaging pattern
  * Describes how two different parts of a message passing system connect and communicate with each other
* Decouple services from direct dependence and allow storage of events in a queue
  * Reliability: if the consuming service goes offline, messages are retained in the queue and can still be processed
  * A message queue can have a single sender/receiver or multiple senders/receivers

![](imgs/slides369.png)

# Priority queue pattern

* Decouple and prioritize requests sent to services
  * Requests with a higher priority are received and processed more quickly than those with a lower priority
  * Useful in applications that offer different service level guarantees
* Control how and when messages are dealt with
  * Different queues, topics, or streams to feed messages to your functions
  * High-priority messages go through expensive services with more capacity

![](imgs/slides370.png)

# That’s all, folks!

# Feedbacks?

# Exams

# -- newsection --

# Hands on AWS

# A tentative organization

Supporting services

Serve (deciding)

BI tools (e.g., Tableau)

Analytics (analyzing)

Networking, etc.

Machine learning

Ingestion (acquiring)

# Identity and Access Management

* Identity and Access Management (IAM)
  * Web service that controls fine-grained access to AWS resources
  * IAM controls who is authenticated and authorized to use resources
* IAM user
  * Unique identity recognized by AWS services and applications
  * Similar to user in an operating system like Windows or UNIX

* IAM role
  * Set of policies for making AWS service requests
  * Trusted entities (e.g., such as IAM users) assume roles
    * Delegate access with defined permissions to trusted entities
    * There is no limit to the number of IAM roles a user can assume
* User vs role
  * User has permanent long-term credentials and is used to directly interact with AWS services
  * Role does not have credentials and cannot make direct requests to AWS services
  * Roles are assumed by authorized entities, such as IAM users

* Alice (i.e., an IAM user) is a firewoman
  * She is the same person with or without her turnout gear
  * As a firewoman (i.e., a role)
    * If she speeds to a house fire and passes a police officer, he isn't going to give her a ticket
    * In her role as a _firewoman_ , she is allowed to speed to the house fire
  * As a private citizen (i.e., another role)
    * When she is off duty, if she speeds past that same police officer, he's going to give her a ticket
    * In her role as a _private citizen_ , she is not allowed to speed

# AWS

* Amazon Web Services (AWS) is a public-cloud platform
* Services can be accessed in multiple ways
  * Web GUI: intuitive point and click access without any programming
    * Intuitive interfaces is part of the attraction of cloud services
    * Tedious if the same actions must be performed repeatedly
  * (REST) Application programming interface (API)
    * Permits requests to be transmitted via Hypertext Transfer Protocol (HTTPS)
  * Software development kits (SDKs) that you install on your computer
    * Access from programming languages such as Python, Java, etc.

# AWS Web console

* We use the AWS Educate program
  * Login with the provided account
  * You got 150$ to work on AWS services
  * Provisioned services charge even if not used

![](imgs/slides371.png)

[https://www.awseducate.com/signin/SiteLogin](https://www.awseducate.com/signin/SiteLogin)

![](imgs/slides372.png)

# AWS CLI

* CLI interface
  * Necessary to install the CLI (version 2)
  * See [https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)

Synopsis

********

aws [options] \<command> \<subcommand> [parameters]

Description

***********

A unified tool to manage your AWS services.

[https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-linux.html](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-linux.html)

![](imgs/slides373.png)

* CLI needs credentials to work
  * Go back to AWS Educate
  * Click on “Account Details”
  * Copy the content into the file ~/.aws/credentials
  * Henceforth, we assume that you have set up the credentials file
  * Credentials expire after some time; you need a manually refresh

![](imgs/slides374.png)

* Run `aws configure`
  * Confirm AWS Access Key ID (press enter)
  * Confirm AWS Secret Access Key (press enter)
  * Set Default region name to `us-east-1`
  * Set Default output format to `json`
* It is also possible to configure an AWS profile
  * A (named) profile is a collection of settings and credentials
  * If profile is specified, its settings and credentials are used to run a command
  * When no profile is explicitly referenced, use `default`
    * We stick to `default`

# Object storage: S3

* Create S3 bucket, the following rules apply for naming buckets
  * Must be between 3 and 63 characters long
  * Can consist only of lowercase letters, numbers, dots (.), and hyphens (-)
  * Must be unique within a partition (i.e., a group of regions)

$ git clone [https://github.com/w4bo/bigdata-aws/](https://github.com/w4bo/bigdata-aws/)

$ cd bigdata-aws/lab01-lambda

$ aws s3api create-bucket --bucket aws-bucket-bigdata2021

$ aws s3 cp datasets/inferno.txt s3://aws-bucket-bigdata2021/inferno.txt

$ aws s3api list-objects --bucket aws-bucket-bigdata2021

[https://s3.console.aws.amazon.com/s3/home?region=us-east-1\#](https://s3.console.aws.amazon.com/s3/home?region=us-east-1)

# -- newsection --

# Data pipelines on AWS Lambda

# Requirements

* To start this lecture, you need to
  * Activate your AWS Educate account
  * Either
    * Install the necessary software
      * git
      * IntelliJ IDEA (with AWS Toolkit and Scala plugins)
      * python
      * java 1.8
      * Docker
      * AWS CLI, AWS SAM CLI
    * Be able to download and run the VM

# AWS SAM CLI

* Serverless Application Model is a framework to build serverless applications
  * A serverless application is a combination of Lambda functions, event sources, etc.
  * Install AWS SAM CLI (on Linux)

sudo group add docker

sudo usermod –aG docker $USER

newgrp docker

sudo chmod 666 /var/run/docker.sock

wget [https://github.com/aws/aws-sam-cli/releases/latest/download/aws-sam-cli-linux-x86_64.zip](https://github.com/aws/aws-sam-cli/releases/latest/download/aws-sam-cli-linux-x86_64.zip)

unzip aws-sam-cli-linux-x86_64.zip -d sam-installation

sudo ./sam-installation/install

sam --version

[https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html)

# AWS services

* AWS Educate (and AWS console)
  * [https://aws.amazon.com/it/education/awseducate/](https://aws.amazon.com/it/education/awseducate/)
  * [https://console.aws.amazon.com/console/home?region=us-east-1](https://console.aws.amazon.com/console/home?region=us-east-1)
* IAM (authentication)
  * [https://docs.aws.amazon.com/IAM/latest/UserGuide/iam-ug.pdf](https://docs.aws.amazon.com/IAM/latest/UserGuide/iam-ug.pdf)
* SDK (software API)
  * [https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/home.html](https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/home.html)
* Lambda (serverless computing and processing)
  * [https://docs.aws.amazon.com/lambda/latest/dg/getting-started.html](https://docs.aws.amazon.com/lambda/latest/dg/getting-started.html)
  * [https://console.aws.amazon.com/lambda/home?region=us-east-1\#/functions](https://console.aws.amazon.com/lambda/home?region=us-east-1#/functions)
* DynamoDB (key-value database)
  * [https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction)
* S3 (object storage)
  * [https://s3.console.aws.amazon.com/s3/home?region=us-east-1](https://s3.console.aws.amazon.com/s3/home?region=us-east-1)

# Case study

Given a dataset of sales per customer

find the products frequently bought together

Dataset sample

%%%%%%%%%%%%%%

[ { customerName: Alice, products: [Pizza, Beer, Diaper] },

{ customerName: Bob, products: [Pizza, Beer, Diaper] },

{ customerName: Charlie, products: [Pizza, Cola] } ]

* The pipeline involves a single transformation
  * A classic mining problem, which one?

# Frequent itemset mining

Dataset sample

%%%%%%%%%%%%%%

[[Pizza, Beer, Diaper],

[Pizza, Beer, Diaper],

[Pizza, Cola]]

* Find sets of items (i.e., itemsets) frequently appearing together
  * __Item__: a product
  * __Itemset__: a set of products
  * __Frequently__: support above threshold
  * __Support__: number of clients buying a set of products
* Complexity: O(2|items|)

{Pizza,Diaper,Beer}

# Case study

Processed dataset sample

%%%%%%%%%%%%%%

[[Pizza, Beer, Diaper],

[Pizza, Beer, Diaper],

[Pizza, Cola]]

Raw dataset sample

%%%%%%%%%%%%%%

[ { customerName: Alice, products: [Pizza, Beer, Diaper] },

{ customerName: Bob, products: [Pizza, Beer, Diaper] },

{ customerName: Charlie, products: [Pizza, Cola] } ]

# Reference pipeline

![](imgs/slides375.png)

![](imgs/slides376.png)

# NOSQL storage: DynamoDB

* Basic DynamoDB components: tables and items
* __Tables__ , collection of (data) items
* __Items__ , a group of attributes that is uniquely identifiable
  * Each table contains zero or more items
    * No limit to the number of items you can store in a table
  * Each item in the table has a unique identifier, or primary key
  * E.g., in the table `people`, each item represents a `person`
    * The primary key consists of one attribute (`fiscalCode`)

* Attributes
  * A data element that is not broken down any further
    * E.g., an item in the `people` table contains attributes `fiscalCode` and `lastName`
  * Most of the attributes are scalar (have only one value)
  * Some of the items have a nested attribute (`address`) up to 32 levels deep
* Schemaless
  * Other than the primary key, a table is schemaless
    * Neither the attributes nor their data types need to be defined beforehand
    * Each item can have its own distinct attributes

* Primary Key
  * To create a table, you must specify the primary key of the table
  * No two items can have the same key
* Two types of primary keys
  * Partition key: a simple primary key composed of one attribute (partition key)
    * Keys are inputs to an internal hash function
    * The hash function determines the physical partition in which the item will be stored
    * E.g., access any item in the `people` table directly by providing the `fiscalCode`
  * Composite primary key: partition key and sort key (two attributes)
    * First attribute is the partition key
    * Second attribute is the sort key
    * Items in same partition key value are stored together and sorted by sort key

![](imgs/slides377.png)

[https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-gsi-overloading.html](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-gsi-overloading.html)

* Secondary Indexes
  * One or more secondary indexes per table
  * Indexes are automatically maintained on add, update, or delete
  * Query data using an alternate key (additionally to queries against primary key)
* Two types of indexes
  * Global secondary has partition and sort keys different from those on table
  * Local secondary has the same partition key but a different sort key
  * Each table has a limited quota of 20 global and 5 local indexes
* How do we shape the schema?
  * [https://cloud.google.com/bigtable/docs/schema-design](https://cloud.google.com/bigtable/docs/schema-design)

* Create a table `frequent-sales` with a composite key
  * `dataset`: String
  * `timestamp`: String

$ aws dynamodb create-table \\

--table-name frequent-sales \\

--attribute-definitions AttributeName=dataset,AttributeType=S AttributeName=timestamp,AttributeType=S \\

--key-schema AttributeName=dataset,KeyType=HASH AttributeName=timestamp,KeyType=RANGE \\

--provisioned-throughput ReadCapacityUnits=1,WriteCapacityUnits=1

$ aws dynamodb list-tables

$ aws dynamodb delete-table --table-name frequent-sales

* Reading data from DynamoDB might not reflect the results of a recent write
* Eventually Consistent Reads (default)
  * Response might include stale data
  * After short time, the response should return the latest data
* Strongly Consistent Reads
  * Response includes the most up-to-date data
  * A strongly consistent read might not be available if there is a network delay or outage
    * In this case, DynamoDB may return a server error (HTTP 500)
  * Strongly consistent reads may have higher latency than eventually consistent reads
  * Strongly consistent reads are not supported on global secondary indexes

* Provisioned mode: specify the \#reads and \#writes per second
  * You have predictable application traffic or traffic ramps gradually
  * You can forecast capacity requirements to control costs
* One read capacity unit
  * One strongly consistent read per second, two eventually consistent reads per second
  * RCUs also depend on the item size (a read is up to 4 KB in size), if item size is 8 KB
    * 2 RCUs to sustain one strongly consistent read per second
    * 1 RCU if you choose eventually consistent reads
* One write capacity unit represents one write per second for an item up to 1 KB in size

Put a new item and get it back

$ aws dynamodb put-item    --table-name frequent-sales    --item '{"dataset": {"S": "sales"}, "timestamp": {"S": "1611226870"}, "bar": {"S": "foobar"}}'

$ aws dynamodb query    --table-name frequent-sales    --key-condition-expression "dataset =:n"     --expression-attribute-values '{":n":{"S":"sales"}}'

# Lambda: create a function

![](imgs/slides378.png)

[https://console.aws.amazon.com/lambda/home?region=us-east-1\#/functions](https://console.aws.amazon.com/lambda/home?region=us-east-1#/functions)

# Lambda: attaching a role

![](imgs/slides379.png)

![](imgs/slides380.png)

![](imgs/slides381.png)

![](imgs/slides382.png)

![](imgs/slides383.png)

# Lambda: create a function

![](imgs/slides384.png)

[https://console.aws.amazon.com/lambda/home?region=us-east-1\#/functions](https://console.aws.amazon.com/lambda/home?region=us-east-1#/functions)

* Manually creating the functions is cumbersome
  * We must copy and paste code
  * No automatic testing
  * No debugging
  * No IDE support (and not all languages are supported)
* Switch to IntelliJ IDEA + AWS Toolkit

# AWS Toolkit

  * Get the latest IntelliJ IDEA
  * Install the `AWS Toolkit`
  * Copy the credentialscp ~/.aws/credentials ~/.aws/config
  * Clone the repo git clone [https://github.com/w4bo/bigdata-aws/](https://github.com/w4bo/bigdata-aws/)
  * Import `lab01-lambda` as a Gradle project
  * Verify that the project builds./gradlew

![](imgs/slides385.png)

* Click on `AWS Explorer`
  * You can see the `helloworld` function
  * Plus `CloudWatch Logs` and `S3`

![](imgs/slides386.png)

* Test the existing code locally
  * With Gradle
  * Or with local Lambda execution
* Deploy a new Lambda function from the existing code
  * Right click on AWS Explorer > Lambda
  * Select `Create new AWS Lambda...`
  * Populate the settings
  * `Create the function`

![](imgs/slides387.png)

[https://aws.amazon.com/lambda/pricing/](https://aws.amazon.com/lambda/pricing/)

* Check the log for errors and pricing
  * AWS Toolkit > CloudWatch Logs
  * Double click on the function name
  * Double click on the log entry

![](imgs/slides388.png)

![](imgs/slides389.png)

# Data pipeline

* Deploy and execute the HelloWorld.java lambda function
* Given the created storage: S3 and DynamoDB
  * Deploy the function `FIM`
  * Deploy the function `Preprocess`
  * Run `ReadDataset.java`
  * Check that the table `frequent-sales` has the FIs for the dataset `sales`
* Some hints
  * Function names are case sensitive
  * Some function need more than 128MB of memory
    * Behold! The higher the RAM, the higher the costs

# 

![](imgs/slides390.png)

![](imgs/slides391.png)

