# MongoDB

### Before we start 

* if we categorized the database solutions then there are mainly two types of database category available     * RDBMS or Relational Database like SQL Server, Oracle etc.
    * another type is NoSQL database like MongoDB, CosmosDB etc.
    
### NoSQL Types

![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/no-sql-types.png)

### What is MongoDB?

* open-source 
* document-based database management tool that 
* stores data in JSON-like formats. 

![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/mongodb2.png)

* It is a highly scalable, 
* flexible, and 
* distributed NoSQL database.
* written in C++
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

### Version History

   * MongoDB is a document-based database which is developed in the C++ programming languages. 
   * The word Mongo is basically derived from Humongous. MongoDB was first developed by a New York-based organization named 10gen in the year of 2007. 
   * Later 10gen changed the name and known as MongoDB Inc as of today. 
   * At the beginning, MongoDB is basically developed as a PAAS (Platform as a Service) database. 
   * But, in the year 2009, it was introduced as an open source database as named MongoDB 1.0. 
   * The below diagram demonstrates the release history of MongoDB till date. 
   * MongoDB 4.0 is the current stable version which is released in February, 2018.
   
![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/mongo-versionhistory.png)

### MongoDB is an open-source document database that provides 
      * high performance, 
      * high availability, and 
      * automatic scaling.
      
  * Its document-oriented data model makes it easier to split up data across multiple servers.
  * MongoDB automatically takes care of balancing data and load across a cluster
  * redistributing documents automatically
  * routing user requests to the correct machines.
  
![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/MONGO-DB-1-01.webp)

### How MongoDB Stores Data?

  * MongoDB stores data in documents in-spite of tables.
  * You can change the structure of records (which is called as documents in MongoDB) simply by adding new fields or deleting existing ones
  * This ability of MongoDB help you to represent hierarchical relationships, to store arrays, and other more complex structures easily. 
  * MongoDB provides high performance, high availability, easy scalability and out-of-the-box replication and auto-sharding.
  
![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/mongodb3.png)
  
### WHAT IS SEMI-STRUCTURED DATA?

  * Semi-structured data is data that does not conform with the formal structure of data.
  * The semi-structured model is a database model where there is no separation between the data and the schema.
  
### WHAT IS A DOCUMENT-ORIENTED DATABASE?

  * document-oriented database is software designed for storing and retrieving information in the form of semi-structured data, also known as documents
  * It replaces the concept of a “row.” By allowing embedded documents and arrays
  * the document-oriented approach makes it possible to represent complex hierarchical relationships with a single record.
  
### KEY FEATURES

* `High Performance`: MongoDB provides high performance data persistence. It supports embedded data models to reduce I/O activity on a database system, as well as indexes for faster queries, and can include keys from embedded documents and arrays

* `High Availability`: To provide high quality availability, MongoDb’s replication facility (known as replica sets) provide both automatic failover and data redundancy. A replica set is a group of MongoDB servers that maintain the same data set and provide both redundancy and increased data availability

* `Automatic Scaling`: MongoDB provides horizontal scalability as part of its core functionality. Automatic sharding distributes data across a cluster of machines, while replica sets can provide eventually-consistent reads for low-latency deployments

### CORE COMPONENTS OF MONGODB

* `Mongod`: As the primary daemon process for the MongoDB system, **Mongod handles data requests, manages data access, and performs background management operations**

* `Mongos`: **Mongos is utilized as a routing service for MongoDB Shard configurations**. This component processes **queries from the application layer** and **determines the data’s location in the sharded cluster** so as to complete the commanded operations. From the perspective of the application, a **Mongos instance behaves identically to any other MongoDB instance**

* `Mongo`: **Mongo is an interactive JavaScript shell interface** for MongoDB and provides an **interface to test queries and operations directly within the database**. Mongo also provides a **fully functional JavaScript environment** to use with MongoDB

### Architecture of MongoDB NoSQL Database

![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/The-architecture-of-MongoDB-NoSQL-Database.webp)

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
  
### BSON and MongoDB

  * BSON is a binary-encoded serialization of JSON-like documents and is designed to be lightweight, traversable, and efficient. 
  * BSON, like JSON, supports the embedding of objects and arrays within other objects and arrays. 
  * MongoDB uses BSON as the data storage and network transfer format for its documents.
  
### Sample Representation of a Document in MongoDB

  * `Document`
  
![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/xDocument.png.pagespeed.ic.4bChw0MYgu.png)

  * `Referenced Documents`  

![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/xReferenced-Documents.png.pagespeed.ic.aw4HszXkJZ.png)

  * `Embedded Documents`
 
 ![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/xEmbedded-Documents.png.pagespeed.ic.HzcoRouTyl.png)
  
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

### DB Objects Comparison

| MongoDB Objects  | SQL Objects |
| ------------- | ------------- |
| Database  | Database (schema)  |
| Collection  | Table  |
| Index  | Index  |
| Document  | Row  |
| Field  | Column  |
| Linking & Embedding  | Joining  |
| Shard  | Partition  |

### Important Features of MongoDB

![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/MONGO-DB-3-01.webp)

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
  
### REPLICATION IN MONGODB

  * Replication is the practice of keeping identical copies of data on multiple servers to keep applications running and data safe. 
  * There are two set-up designs within MongoDB: 
         * a Replica Set with **Replication Cluster** and 
         * a Replica Set with **Arbiter**.
  * All replica set members send heartbeats (pings) to each other every two seconds.
  * If a heartbeat does not return within ten seconds, the other servers mark the unresponsive server as inaccessible.
  
### Replica Set with Replication Cluster

  * A cluster of MongoDB servers that implements master-subordinate replication for automated failover
  * When the primary server is unavailable, it triggers an election for one of the remaining secondary servers to act as the new primary server.
  
  ![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/Secondary.png)
  
### Replica Set with Arbiter

  * Arbiter is a Mongod instance where a server is in the replica set but does not hold data.
  * The arbiter participates in elections as a tie-breaker if a replica set has an even number of servers
  
    ![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/Arbiter.png)
    
### SHARDING IN MONGODB

  * MongoDB’s sharding is the ability to break up a collection in to subsets of data to store them across multiple shards.
  * This allows the application to grow beyond the resource limits of a standalone server or replica set.
  
#### Basic Recommended Sharded Cluster for MongoDB

  ![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/Basic-Recommended-Sharded-Cluster-for-MongoDB.png)
  
  * `Sharded cluster`: 
  
     * The router (Mongos process) acts as a gatekeeper for all requests coming from the client. 
     * It resolves the requests by using the configuration servers to get the metadata information of each shard, then routes the query to the appropriate shards, and finally combines the results given by the shard(s) to return to the client
  
  * `Router in sharded cluster`: 
  
     * As shown above, more than one Mongos process runs as a router. 
     * If utilizing more than one router, both should be configured under a load balancer for an efficient production environment
  
  * `Configuration server in sharded cluster`: 
  
     * The Mongod process runs as a configuration server that keeps meta data, meaning it makes the decision of which data should be extracted from which shard

  * `Shard in sharded cluster`: 
     
     * Each shard is essentially a replica set that holds a portion of data. 
     * To avoid losing any data, it maintains a copy of its data on all secondary servers. 
     * In this sense, a collection in MongoDB is stored in multiple parts across multiple shards; to access the full collection, the data must be retrieved from all shards, as shown below
     
     ![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/Sharded-Cluster.png)
     
### Difference Between Shard and Replication
 
`Shared`

  * The shard provides the ability to partition the data and store it across multiple servers.
  * This increases the hardware capacity of the cluster, meaning that resources are not limited to a single machine.
  
  `Replication`
  
  * is a duplicate copy of the data in full to be used in the event of a hardware failure.
  
### DEFAULT PORTS FOR MONGODB

  | Default Port  | Description |
| ------------- | ------------- |
| 27017  | The default port for Mongod and Mongos instances. Change this port with port or -port  |
| 27018  | The default port when running with the -shardsvr runtime operation or the shardsvr value for the clusterRole setting in a configuration file  |
| 27019  | The default port when running with the -configsvr runtime operation or the configsvr value for the clusterRole setting in a configuration file  |
| 28017  | The default port for the web status page. The web status page is always accessible at a port number that is 1000 times greater than the determining port  |

### ENABLE AUTHENTICATION

  * Authentication is the process of proving the identity of a user.
  * Use the following script to create two users, one with root role permissions and one with readwrite role permissions.
  * The root role user will hold top level permissions in MongoDB, while the readwrite role permissions allow the user to perform CRUD on collections.
  
     * `Root role user`: Apply the following command in the Mongo shell to create a new user (“rootuser” with a password “12345”) who has a root role on the admin database
use admin

          * db.createUser({user:"rootuser",pwd:"12345", roles:[{role:"root",db:"admin"}]})

     * `Readwrite user`: Apply the following command in the Mongo shell to create a new user (“webuser” with password “12345”) who has readwrite permissions on the application database (“companydb” used in this example) use companydb
     
          * db.createUser({user:"webuser", pwd:"12345", roles:[ "readWrite" ]})

### Why do you need MongoDB technology?

  * scalability -> MongoDB has exceptional scalability
  * It makes it easy to fetch the data and provides continuous and automatic integration. 
  * No downtime while the application is being scaled
  * Performs in-memory processing
  * Text search
  * Graph processing
  * Global replication
  * Economical
  
### Use Cases -- why and where?

  * E-Commerce type of product-based applications
  * Blog and Content Management systems
  * High Speed logging, caching etc in the Real time
  * Need to maintain location wise Geospatial data
  * For maintains data related to the Social and Networking types
  * If application is a loosely coupled mechanism – means design may change at any point of time.

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
   
   ![MongoDB](https://github.com/gtl-madhav/MongoDB/blob/master/images/mongo-db-2-01.webp)
   
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
  
  * CRUD (Create, Read, Update & Delete) operations with the data.
  * MongoDB is a Schema less document type database.
  * MongoDB support field, range based query, regular expression or regex etc for searching the data from the stored data.
  * MongoDB is very easy to scale up or down.
  * MongoDB basically uses internal memory for storing the working temporary datasets for which it is much faster.
  * MongoDB support primary and secondary index on any fields.
  * MongoDB supports replication of database.
  * We can perform load balancing in the MongoDB by using Sharding. It scales the database horizontally by using Sharding.
  * MongoDB can be used as a file storage system which is known as a GridFS.
  * MongoDB provides the different ways to perform aggregation operations on the data like aggregation pipeline, map reduce or single objective aggregation commands.
  * MongoDB can store any type of file which can be any size without effecting our stack
  * MongoDB basically use JavaScript objects in place of procedure.
  * MongoDB support special collection type like TTL (Time-To-Live) for data storage which expire at a certain time
  * The dynamic database schema used in MongoDB is called the BSON
  
### MongoDB Limitations

  * Since MongoDB is not as strong ACID (Atomic, Consistency, Isolation & Durability) as compare to the most RDBMS systems.
  * It can’t handle complex transactions
  * In MongoDB, there is not provision for Stored Procedure or functions or trigger so there are no chances to implement any business logic in the database level which can be done in any RBMS systems.
  
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
  
### Platform And Language Support

  * C,C++,C# & .NET, Java , Node.js , Perl , PHP, PHP Libraries, Frameworks, and Tools., Python, Ruby, Mongoid (Ruby ODM)

`Source` : https://intellipaat.com/blog/what-is-mongodb/ </br>
`Source` : https://www.3pillarglobal.com/insights/what-is-mongodb </br>
`Source` : https://www.dotnettricks.com/learn/mongodb/what-is-mongodb-and-why-to-use-it
