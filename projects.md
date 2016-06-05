---
layout: page
section-type: null
title: Projects
---
## Projects

[Ferma](http://wiki.syncleus.com/index.php/Ferma)

An ORM / OGM for the TinkerPop graph stack. The Ferma project has been created as an alternative to the TinkerPop Frames project. Redesigned for performance and additional features. Annotated classes in Ferma have their abstract methods implemented using code generation during start-up with Byte Buddy, avoiding the need for proxy classes. This in turn significantly improves performance when compared with TinkerPop Frames.

[GRAIL](http://wiki.syncleus.com/index.php/GRAIL)

GRAIL is an algorithm implementation layer that allows arbitrary algorithms to be backed, and executed, from a graph database. The backing graph database can be either an on-disk server instance or a purely local in-memory instance. This allows generic tools to be interfaced to accomplish an assortment of extensions such as: distributed processing, visualizations, indexing, graph traversal, SPARQL queries, and much more.

[dANN](http://wiki.syncleus.com/index.php/dANN)

An Artificial Intelligence and Genetic Algorithms Library. dANN, has been under constant development since its inception and now covers a large range of industry standard algorithms including Artificial Neural Networks, Graphical Models, Signal Processing, Naive Classifiers, and much more.

[AIDE](http://wiki.syncleus.com/index.php/AIDE)

An automated Inference Engine software suite that includes distributed server engine’s as well as an easy to use GUI for administration and processing of data sets. It is based off of the dANN library. It performs inference on any database with any schema  with a minimal amount of configuration needed.

[Sporkie](http://wiki.syncleus.com/index.php/Sporkie)

Sporkie is a challenge-response anti-spam filter. It used a CAPTCHA based challenge to ensure the user who sends an e-mail is a human, and not a bot. The email was held in a queue until a proper response was received. If a response wasn’t received within a certain amount of time the email was deemed spam and Permanently archived.