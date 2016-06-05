---
layout: post
section-type: post
title: GRAIL Project Initiated
category: projects
tags: [ 'GRAIL', 'Projects' ]
---

dANN is being split up into multiple smaller projects and rewritten. The GRAIL project will serve as the new core layer for dANN and other libraries pulled out from dANN.

GRAIL is an algorithm implementation layer that allows arbitrary algorithms to be backed, and executed, from a graph database. The backing graph database can be either an on-disk server instance or a purely local in-memory instance. This allows generic tools to be interfaced to accomplish an assortment of extensions such as: distributed processing, visualizations, indexing, graph traversal, SPARQL queries, and much more.

GRAIL uses a native TinkerPop stack, this means it can support virtually every graph database available to you. A few examples of supported Graph Databases are as follows.

* Titan
* Neo4j
* OrientDB
* MongoDB
* Oracle NoSQL
* TinkerGraph

TinkerPop also provides several tools which can be used to work with GRAIL backed algorithms.

* Furnace – Graph analysis utilities
* Frames – An object-to-graph mapping similar to ORM for relational databases
* Pipes – A data-flow framework for splitting, merging, filtering, and transforming of data
* Gremlin – A graph query language
* Blueprints – A standard graph API

Finally, depending on the choice of a graph database backend, it is possible to utilize any of the following features.

* Elastic and linear scaling capabilities
* ACID and BASE consistency models.
* Distributed data, replication, high availability, and fault tolerance.
* Faunus Gremlin-based distributed graph analytics, backed by an Hadoop cluster.
* Direct Apache Hadoop integration providing graph analytics, reporting, and ETL features
* Indexing and search utilities including: ElasticSearch, Solr, and Lucene
* A Titan backend can support all the above features.
