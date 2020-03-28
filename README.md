# Awesome Solr [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Solr is a Web Service (REST) that provides applications API access to create and manage search indices (Collections) that behave like a NoSQL storage for Documents with Fields. The data saved in a collection of Solr documents can be queried using a variety of query syntaxes, most commonly the Lucene query syntax, dismax, or edismax. Solr's web server based on Jetty wraps the Lucene API with a web service so that developers and applications don't need to do the housekeeping involved in managing the index files themselves. 

A curated list of awesome [Apache Solr](http://lucene.apache.org/solr/) packages and resources. Maintained by Rahul Singh of [Anant](http://anant.us). Feel free contact me if you'd like to collaborate on this and other awesome lists. [Awesome Cassandra](https://github.com/Anant/awesome-cassandra) , [Awesome Solr](https://github.com/Anant/awesome-solr), [Awesome Lucene](https://github.com/Anant/awesome-lucene)

## Contents

- [General](#general)

- [Packages](#packages)
  - [Interfaces](#interfaces) User Interfaces for Solr.
  - [Tools](#tools) Applications / Plugins that use Solr.
  - [Projects](#projects) Other projects that use Solr.
  - [Clients](#clients) Programming Language Specific Clients for Solr.
  
- [Resources](#resources)
  - [Documentation](#documentation) Official / unofficial documentation. 
  - [Books](#books) Popular books about Solr.
  - [Tutorials](#tutorials) Step by step tutorials on Solr.
  - [Web Sites](#web-sites) Sites ( not blogs ) on Solr.
  - [Blogs](#blogs) from Solr experts.
  - [Docker Images](#docker-images) Docker Images / Composures w/ Solr.
  - [Videos](#videos) Videos on Solr.

## General

  - [Apache Solr](http://lucene.apache.org/solr/)
  - [Wikipedia: Apache Solr](https://en.wikipedia.org/wiki/Apache_Solr)

## Packages


### Interfaces
  - [Appleseed Search Web User](https://github.com/Appleseed/search-web-user) - Part of the [Appleseed Portal open source project](https://appleseedapp.net/Home.aspx).
  - [Blacklight](http://projectblacklight.org/) A multi-institutional open-source collaboration building a better discovery platform framework.
  - [Solr PHP UI](https://www.opensemanticsearch.org/solr-php-ui/) Solr client and user interface for search (UI).
  - [AJAX Solr](https://github.com/evolvingweb/ajax-solr) AJAX Solr is a JavaScript library for creating user interfaces to Apache Solr.
  - [Spyglass](https://github.com/o19s/Spyglass) Simple search results with Solr and EmberJS.
  - [Splainer](https://github.com/o19s/splainer-search) Angular JS Solr and Elasticsearch Diagnostic Search Services.
  - [Solrstrap](https://github.com/fergiemcdowall/solrstrap) Solrstrap is a Query-Result interface for Solr. 
  - [ngSolr](http://www.davismarques.com/projects/ngsolr/) Easy faceted search for Apache Solr.
  - [SOLR-AJAX](https://bitbucket.org/esrc/eaccpf-ajax) Single Page Faceted Search Interface to Apache Solr/Lucene.
  - [Solstice](https://github.com/front/solstice) A simple Solr wrapper for AngularJS apps.
  - [SolrDora](https://github.com/hectorcorrea/solrdora) A quick and easy way to explore the data in your Solr core.

### Tools

  - [WPSolr Search Engine WordPress Plugin](https://wordpress.org/plugins/wpsolr-search-engine/) Search 10 times faster with Elasticsearch or Apache Solr with lots of data - WPSOLR.
  - [Apache Solr Search Drupal Plugin](https://www.drupal.org/project/apachesolr) This module integrates Drupal with the Apache Solr search platform. 
  - [Drupal Search API Solr Plugin](https://www.drupal.org/project/search_api_solr) This module provides a Solr backend for the [Search API](https://www.drupal.org/project/search_api) module.
  - [Solr proxies](https://github.com/evolvingweb/ajax-solr/wiki/Solr-proxies) Simple solr proxies implemented in PHP, Node.js, Java, or NGINX.
  
### Projects

  - [Transformalize](https://github.com/dalenewman/Transformalize/) This tool expedites mundane data processing tasks like cleaning, reporting, and denormalization. Specifically can quickly process data from SQL/MySQL/PostgreSQL to Solr/ Elasticsearch.
  - [JesterJ](https://github.com/nsoft/jesterj) A new highly flexible, highly scaleable document ingestion system.
  - [Spark-Solr](https://github.com/lucidworks/spark-solr) Tools for reading data from Solr as a Spark RDD and indexing objects from Spark into Solr using SolrJ.
  - [Flink Solr Connector](https://github.com/naveenmadhire/flink-solr-connector) Apache Flink Sink for Solr.
  - [Apache Flume](https://flume.apache.org/) Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data. 
  - [Storm Solr](https://github.com/lucidworks/storm-solr) Tools for building Storm topologies for indexing data into SolrCloud.
  - [Kafka Connector for Solr Sink(https://github.com/MSurendra/kafka-connect-solr) Kafka Connect Solr for writing data to Solr. 
  - [SolrMQ](https://github.com/tangentlabs/SolrMQ) SolrMQ is a plugin for Solr that allows you to send updates to Solr using a AMQP messaging queue. We use the RabbitMQ library.


### Clients

  - [SolrJ](https://cwiki.apache.org/confluence/display/solr/Using+SolrJ) Java Solr Client.
  - [SolrNet](https://github.com/mausch/SolrNet) .NET Solr Client. 
  - [Solr Scala Client](https://github.com/takezoe/solr-scala-client).
  - [solrs](https://github.com/inoio/solrs) An async, non-blocking solr client for java/scala, providing a query interface like SolrJ.
  - [Scalikesolr](https://github.com/seratch/scalikesolr) Apache Solr. Client for Scala/Java.
  - [Solr Play Scala Client](https://github.com/Ramzi-Alqrainy/solr-play-scala-client) A Scala library in Play framework for indexing and searching documents within an Apache Solr.
  - [Python Solr Clients](https://wiki.apache.org/solr/SolPython) Reference to multiple Python Solr Clients. 
  - [Python:SolrClient](https://github.com/moonlitesolutions/SolrClient) SolrClient is a simple python library for Solr; built in python3 with support for latest features of Solr.
  - [mysolr](http://mysolr.readthedocs.io/en/latest/) mysolr was born to be a fast and easy-to-use client for Apache Solr’s API and because existing Python clients didn’t fulfill these conditions.
  - [rsolr](https://github.com/rsolr/rsolr) A ruby client for Solr.
  - [Sunspot](http://sunspot.github.io/) Solr-powered search for Ruby objects.
  - [Solarium](http://www.solarium-project.org/) Solarium is a Solr client library for PHP.
  - [Solr PHP extension](http://php.net/manual/en/intro.solr.php) The Solr extension allows you to communicate effectively with the Apache Solr Server in PHP.
  - [Go-Solr](https://github.com/rtt/Go-Solr) A solr library written in Go.
  - [go-solr](https://github.com/vanng822/go-solr) Solr client in Go, core admin, add docs, update, delete, search and more.
  - [Gora](https://github.com/wirelessregistry/gora) A simple Solr client for Go.
  - [CPAN Apache::Solr](http://search.cpan.org/~markov/Apache-Solr/) Perl Apache Solr.
  - [Solrclj](https://github.com/mlehman/solrclj) A Clojure client for Apache Solr.
  - [flux](https://github.com/mwmitchell/flux) A Clojure based Solr client.
  - [solr-node-client](https://github.com/lbdremy/solr-node-client) A solr client for node.js. A solr client for indexing, adding, deleting,committing and searching documents within an Apache Solr installation


## Resources

### Documentation

  - [Official Solr Documentation](http://lucene.apache.org/solr/resources.html#documentation)
  - [Solr Reference Guide](https://cwiki.apache.org/confluence/display/solr/Apache+Solr+Reference+Guide)
  - [Solr Community Wiki](https://wiki.apache.org/solr)

### Books

TODO : Need to get more books, and then order by reading level. 

  - [Apache Solr Enterprise Search Server, 3rd Edition](https://www.amazon.com/Apache-Solr-Enterprise-Search-Server/dp/1782161368/)
  - [Scaling Big Data with Hadoop and Solr - Second Edition](https://www.amazon.com/Scaling-Big-Data-Hadoop-Solr/dp/1783553391/)
  - [Apache Solr: A Practical Approach to Enterprise Search](https://www.amazon.com/Apache-Solr-Practical-Approach-Enterprise/dp/1484210719/)
  - [Apache Solr Search Patterns](https://www.amazon.com/Apache-Search-Patterns-Jayant-Kumar/dp/1783981849/)
  - [Apache Solr: Beginner's Guide](https://www.amazon.com/Apache-Beginners-Guide-Alfredo-Serafini/dp/1782162526/)
  - [Apache Solr: Essentials](https://www.amazon.com/Apache-Solr-Essentials-Andrea-Gazzarini/dp/1784399647/)
  - [Mastering Apache Solr]
  - [Solr in Action]
  - [Instant Apache Solr for Indexing Data How-to]
  - [Taming Text]
  - [Solr Cookbook - Third Edition]
  - [Scaling Solr](https://www.amazon.com/Scaling-Apache-Hrishikesh-Vijay-Karambelkar/dp/1783981741/)
  - [Enterprise Lucene & Solr](https://www.amazon.com/Enterprise-Lucene-Solr-Lajos-Moczar/dp/0133521761/)
  - [Apache Solr 4 Cookbook]
  - [Apache Solr 3.1 Cookbook]
  - [Apache Solr 5.x: Beginner's Guide](https://www.amazon.com/Apache-Solr-5-x-Beginners-Guide/dp/1785282433/)
  - [Einführung in Apache Solr (German)]

### Tutorials

  - [Solr Quickstart](http://lucene.apache.org/solr/quickstart.html) 
  - [Solr Tutorial](http://www.solrtutorial.com/) The goal of SolrTutorial.com is to provide a gentle introduction into Solr.
  - [Solr tutorial](http://yonik.com/solr-tutorial/) by Yonik Seely, creator of Solr. 
  - 

### Websites

  - [Search Hub](https://lucidworks.com/resources/searchhub/#hub/) Search across millions of pages related to Search.
  - [Solr Start](http://www.solr-start.com/) accelerating your proficiency with Solr search engine.

### Blogs 
  
  - [Solr'n Stuff](http://yonik.com/) Yonik Seely's Blog. Creator of Solr. 
  - [Open Source Connections](http://opensourceconnections.com/blog/) Experts on Solr. 
  - [Lucidworks Blog](https://lucidworks.com/blog/) Blog by Lucidworks. 
  - [Sematext Blog](https://sematext.com/blog/) Blog by Sematext. 


### Docker Images
  - [solr](https://hub.docker.com/_/solr/) Official. Supports 5.x and 6.x.
  - [2degrees/solr4](https://github.com/2degrees/docker-solr4) Supports 4.x.
  - [search-stack](https://github.com/Appleseed/search-stack) Appleseed Search Stack Docker composition. Uses Solr, Elasticsearch, MongoDB, Mono, DotNet, ASPNet, NGINX, MySQL, PostgreSQL.

### Videos
  - TODO 

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).





