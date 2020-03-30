# MongoDB

### What is MongoDB?

* open-source 
* document-based database management tool that 
* stores data in JSON-like formats. 
* It is a highly scalable, 
* flexible, and 
* distributed NoSQL database.
* non-structured query language
* one of the most powerful NoSQL systems and databases around
* Expressive Query Language 
* Strong Consistency 
* Enterprise Management & Integrations
* Always On, Global Deployements
* Scalability & Performance

### What is MongoDB Continue !

* Being a NoSQL tool means that it does **not use the usual rows and columns** that you so much associate with the relational database management. 
* It is an architecture that is built on **collections and documents**.
* The basic unit of data in this database consists of a set of **key–value pairs**.
* It allows documents to have different fields and structures.
* This database uses a **document storage** format called **BSON (Binary JSON) Serialization** which is a binary style of JSON documents.
* This It **adds support for data types like Date and binary** that aren't supported in JSON
* The **data model** that MongoDB follows is a **highly elastic** one that lets you **combine and store data** of multivariate types **without having to compromise on the powerful indexing options, data access, and validation rules.**
* There is **no downtime** when you want to **dynamically modify the schemas**. 
* What it means that you can **concentrate more on making your data work harder** rather than spending more time on preparing the data for the database.
* **Users love MongoDB because it offers the fastest time to value compared to any other DBMS technology**

### Architecture of MongoDB NoSQL Database

`Database` 
  * In simple words, it can be called the **physical container for data**. Each of the databases has its **own set of files** on the file system with **multiple databases existing on a single MongoDB server**.
  
`Collection`
  * A **group of database documents can be called a collection**.
  * The **RDBMS equivalent to a collection is a table**. 
  * The **entire collection** exists within a **single database**.
  * There are **no schemas when it comes to collections**. 
  * Inside the **collection**, **various documents** can have varied fields, but mostly the documents within a collection are meant for the same purpose or for serving the same end goal.
  
`Document`
  * A **set of key–value pairs** can be designated as a **document**. 
  * **Documents** are associated with **dynamic schemas**.
  * The **benefit of having dynamic schemas** is that a document in a **single collection does not have to possess the same structure or fields**.
  * Also, the **common fields in a collection’s document can have varied types of data**.
  
###  What makes it different from RDBMS?

  * You can directly compare the MongoDB NoSQL with the RDBMS and map the varied terminologies in the two systems 
       * The RDBMS **table** is a MongoDB **collection** 
       * the **column** is a **field**
       * the **tuple/row** is a **document**
       * the **table join** is an **embedded document**.
       * The typical schema of a relational database shows the number of tables and the relationship between the tables
       * but **MongoDB does not** follow the **concept of relationship**.
      
| MongoDB  | RDBMS |
| ------------- | ------------- |
| Document-oriented and non-relational database  | Relational database  |
| Document based  | Row based  |
| Field based  | Column based  |
| Collection based and key–value pair  | Table based  |
| Gives JavaScript client for querying  | Doesn’t give JavaScript for querying  |
| Relatively easy to setup  | Comparatively not that easy to setup  |
| Unaffected by SQL injection  | Quite vulnerable to SQL injection  |
| Has dynamic schema and ideal for hierarchical data storage  | Has predefined schema and not good for hierarchical data storage  |
| 100 times faster and horizontally scalable through sharding  | By increasing RAM, vertical scaling can happen  |

### Important Features of MongoDB

  * `Queries` :: It supports ad-hoc queries and document-based queries.
  * `Index Support` :: Any field in the document can be indexed.
  * `Replication` :: 
      * It supports Master–Slave replication. 
      * MongoDB uses native application to maintain multiple copies of data. 
      * Preventing database downtime is one of the replica set’s features as it has self-healing shard.
  * `Multiple Servers` :: 
      * The database can run over multiple servers. 
      * Data is duplicated to foolproof the system in the case of hardware failure.
  * `Auto-sharding` :: 
      * This process distributes data across multiple physical partitions called shards. 
      * Due to sharding, MongoDB has an automatic load balancing feature.
  * `MapReduce` :: It supports MapReduce and flexible aggregation tools.
  * `Failure Handling` :: 
      * In MongoDB, it’s easy to cope with cases of failures. 
      * Huge numbers of replicas give out increased protection and data availability against database downtime like rack failures, multiple machine failures, and data center failures, or even network partitions.
  * `GridFS` :: Without complicating your stack, any sizes of files can be stored. GridFS feature divides files into smaller parts and stores them as separate documents.
  * `Schema-less Database` :: It is a schema-less database written in C++.
  * `Document-oriented Storage` :: It uses BSON format which is a JSON-like format.
  * `Procedures` :: MongoDB JavaScript works well as the database uses the language instead of procedures.
  
### Why do you need MongoDB technology?

  * scalability -> MongoDB has exceptional scalability
  * It makes it easy to fetch the data and provides continuous and automatic integration. 
  * No downtime while the application is being scaled
  * Performs in-memory processing
  * Text search
  * Graph processing
  * Global replication
  * Economical
  
### the business requirements.
  
  * MongoDB provides the right mix of technology and data for competitive advantage.
  * It is most suited for mission-critical applications since it considerably reduces risks.
  * It increasingly accelerated the time to value (TTV) and lowered the total cost of ownership.
  * It builds applications that are just not possible with traditional relational databases.
  
### Advantages of MongoDB

  * Distributed Data Platform
      * geographically distributed data centers and cloud regions,
      * ensuring new levels of availability and scalability
      * With no downtime & without changing your application
      * MongoDB scales elastically in terms of data volume and throughput.
      * gives you enough flexibility across various data centers with good consistency.
  * Fast and Iterative Development
      * A flexible data model with dynamic schema
      * with powerful GUI and command line tools
      * makes it fast for developers to build and evolve applications
      * Automated provisioning enables continuous integration and delivery for productive operations
  * Flexible Data Model
      * MongoDB stores data in flexible JSON-like documents
      * data persistence and combining easy
      * objects in your application code is mapped to the document model -> working with data becomes easy
      * Needless to say that schema governance controls, data access, complex aggregations, and rich indexing functionality are not compromised in any way.
      * Without downtime
      * one can modify the schema dynamically
  * Reduced TCO (Total Cost of Ownership)
      * Atlas Cloud service
      * Costs are significantly lowered as MongoDB runs on commodity hardware
      * The technology gives out on-demand, pay-as-you-go pricing with annual subscriptions, along with 24/7 global support.
  * Integrated Feature Set
      * One can get a variety of real-time applications because of analytics and data visualization
      * event-driven streaming data pipelines
      * text and geospatial search
      * graph processing
      * in-memory performance
      * global replication reliably and securely
  * Long-term Commitment
      * It has garnered over 30 million downloads
      * 4,900 customers
      * 1,000 partners
      
  * MongoDB querying style is dynamic on documents as it is a document-based query language that can be as utilitarian as SQL
  * MongoDB is easy to scale
  * there is no need to convert or map application objects to database objects
  * It deploys the internal memory for providing faster access to data and storing the working set.
  * The cost of managing traditional databases is high. Mistakes made during routine maintenance are responsible for 80 percent of application downtime.
  
###  Frequently Used Commands in MongoDB

  * Database Creation : Use Database_name
  * Dropping Databases : db.dropDatabase()
  * Creating a Collection : db.createCollection(name, options)
  * Showing Collections : shell you can type: db.getCollectionNames()
  * $in Operator : The $in operator selects those documents where the value of a field is equal to the value in the specified array. --> { field: { $in: [<value1>, <value2>, … <valueN> ] } }
  * Projection : Often you need only specific parts of the database rather than the whole database. Find()--> db.COLLECTION_NAME.find({},{KEY:1})
  * Date Operator : Date() – It returns the current date as a string. & New Date() – It returns the current date as a date object.
  * $not Operator : $not does a logical NOT operation on the specified <operator-expression> and selects only those documents that don’t match the <operator-expression>. --> { field: { $not: { <operator-expression> } } }
  * Delete Commands : 
      * collection.remove() – It deletes a single document that matches a filter.
      * db.collection.deleteOne() – It deletes up to only a single document even if the command selects more than one document.
      * db.collection.deletemany() – It deletes all the documents that match the specified filter.
  * Where Command : $where
  * The forEach Command : cursor.forEach(function)

### Where can you use MongoDB NoSQL database?

  * MongoDB NoSQL database can be extensively used for Big Data and Hadoop applications for working with humongous amounts of NoSQL data that is a major portion of Big Data
  * MongoDB can also be successfully deployed for social media and mobile applications for parsing all streaming information which is in the unstructured format. 
  * Content management and delivery also sees extensive use for the MongoDB NoSQL database
  * Other domains are user data management and data hubs.
  
### What is the scope of MongoDB NoSQL?

  * One of the biggest insurance companies on earth MetLife is extensively using MongoDB for its customer service applications;
  * the online classifieds search portal, Craigslist is deeply involved in archiving its data using MongoDB.
  * One of the most hailed brands in the media industry, The New York Times is using MongoDB for its photo submissions and the application that is deployed for form-building.

`Source` : https://intellipaat.com/blog/what-is-mongodb/
