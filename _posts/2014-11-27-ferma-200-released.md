---
layout: post
section-type: post
title: The FERMA Project has Been Released
category: projects
tags: [ 'ferma' ]
---

Syncleus released Ferma version 2.0.0 today, the first official version release.

The Ferma project has been created as an alternative to the TinkerPop Frames project. Redesigned for performance and additional features. Unlike with Frames, annotated classes in Ferma have their abstract methods implemented using code generation during start-up with Byte Buddy, avoiding the need for proxy classes. This in turn significantly improves performance when compared with TinkerPop Frames. Ferma offers several new annotated method types in addition to those provided by TinkerPop Frames. Ferma is designed to easily replace TinkerPop Frames in existing code, as such, the annotations provided by Ferma are a super-set of those provided by TinkerPop Frames.

Ferma is built directly on TinkerPop Blueprints with no dependency on TinkerPop Frames. This ensures all the TinkerPop features and compatabilies are preserved, but with a high-performance drop-in replacement for Frames. The TinkerPop suite provides several tools which can be used to work with the Ferma engine.

* Furnace – Graph analysis utilities
* Pipes – A data-flow framework for splitting, merging, filtering, and transforming of data
* Gremlin – A graph query language
* Blueprints – A standard graph API

Ferma also supports any of the many databases compatible with TinkerPop including the following.

* Titan
* Neo4j
* OrientDB
* MongoDB
* Oracle NoSQL
* TinkerGraph

For more information check out the [main project page](http://wiki.syncleus.com/index.php/Ferma).
