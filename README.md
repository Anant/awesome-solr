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


## Interfaces

  - [Appleseed Search Web User](https://github.com/Appleseed/search-web-user) - Part of the [Appleseed Portal open source project](https://appleseedapp.net/Home.aspx). 
    - Last Commit: 2/2018 / Checked: 3/28/2020.
  - [Blacklight](http://projectblacklight.org/) - Multi-institutional open-source collaboration building a better discovery platform framework. 
    - Last Commit: 3/2020 / Checked: 3/28/2020.
  - [Solr PHP UI](https://www.opensemanticsearch.org/solr-php-ui/) Solr client and user interface for search (UI).
  - [AJAX Solr](https://github.com/evolvingweb/ajax-solr) - A JavaScript library for creating user interfaces for Apache Solr. 
    - Last Commit: 4/2019 / Checked: 3/28/2020.
  - [Spyglass](https://github.com/o19s/Spyglass) - Simple search results with Solr and Ember. 
    - Project is no longer maintained as of 3/2019, available for adoption.
    - Last Commit: 3/2019 / Checked: 3/28/2020.  
  - [Splainer](https://github.com/o19s/splainer-search) - Solr and Elasticsearch Diagnostic Search Services built on Angular.
    - Last Commit: 1/2020 / Checked: 3/28/2020.
  - [Solrstrap](https://github.com/fergiemcdowall/solrstrap) - A Query-Result interface for Solr built on HTML/CSS/JS.
    - Last Commit: 4/2017 / Checked: 3/28/2020.
  - [ngSolr](http://www.davismarques.com/projects/ngsolr/) - Easy faceted search for Apache Solr built using Angular.
    - Last Commit: 4/2016 / Checked: 3/28/2020.
  - [SOLR-AJAX](https://bitbucket.org/esrc/eaccpf-ajax) - SPA Faceted Search Interface to Apache Solr/Lucene.
    - Last Commit: 3/2014 / Checked: 3/28/2020.
  - [Solstice](https://github.com/front/solstice) - A simple Solr wrapper for AngularJS apps.
    - Last Commit: 11/2017 / Checked: 3/28/2020.
  - [SolrDora](https://github.com/hectorcorrea/solrdora) - A quick and easy way to explore the data in your Solr core written in Go.
    - Last Commit: 10/2019 / Checked: 3/28/2020.
  - (DISCONTINUED) [WPSolr Search Engine WordPress Plugin](https://wordpress.org/plugins/wpsolr-search-engine/) - Search 10 times faster with Elasticsearch or Apache Solr with lots of data.
    - Checked: 3/28/2020.
  - [Apache Solr Search Drupal Plugin](https://www.drupal.org/project/apachesolr) - This module integrates Drupal with the Apache Solr search platform. 
    - Last Commit: 3/2020 / Checked: 3/28/2020. 
  - [Drupal Search API Solr Plugin](https://www.drupal.org/project/search_api_solr) - This module provides a Solr backend for the [Search API](https://www.drupal.org/project/search_api) module.
    - Last Commit: 2/2020 / Checked: 3/28/2020.
    
## Tools

  - [Solr proxies](https://github.com/evolvingweb/ajax-solr/wiki/Solr-proxies) - Links to simple solr proxies implemented in PHP, Node.js, Java, or NGINX.
    - Last Commit: 4/2015 / Checked: 3/28/2020.
  
## Projects

  - [Transformalize](https://github.com/dalenewman/Transformalize/) - Expedites mundane data processing tasks like cleaning, reporting, and denormalization. Can quickly process data from SQL/MySQL/PostgreSQL to Solr/ Elasticsearch.
    - Last Commit: 3/2020 / Checked: 3/28/2020.
  - [JesterJ](https://github.com/nsoft/jesterj) A new highly flexible, highly scaleable document ingestion system.
    - Last Commit: 1/2020 / Checked: 3/28/2020.
  - [Spark-Solr](https://github.com/lucidworks/spark-solr) - Tools by Lucidworks for reading data from Solr as a Spark RDD and indexing objects from Spark into Solr using SolrJ.
    - Last Commit: 3/2020 / Checked: 3/28/2020.
  - (DISCONTINUED) Flink Solr Connector - Naveen Madhire's Apache Flink Sink for Solr.
    - Checked: 3/28/2020.
  - [Apache Flume](https://flume.apache.org/) - Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data. 
    - Last Release: 1/2019 / Checked: 3/28/2020.
  - [Storm Solr](https://github.com/lucidworks/storm-solr) - Tools by Lucidworks for building Storm topologies for indexing data into SolrCloud.
    - Last Commit: 4/2018 / Checked: 3/28/2020.
  - [Kafka Connector for Solr Sink](https://github.com/MSurendra/kafka-connect-solr) - Kafka Connect Solr for writing data to Solr. 
    - Last Commit: 6/2016 / Checked: 3/28/2020.
  - [SolrMQ](https://github.com/tangentlabs/SolrMQ) SolrMQ is a plugin for Solr that allows you to send updates to Solr using a AMQP messaging queue. We use the RabbitMQ library.
    - Last Commit: 8/2014 / Checked: 3/28/2020.

## Clients

### Java

  - [SolrJ](https://lucene.apache.org/solr/guide/8_5/using-solrj.html) - Java Solr Client.

### .NET

  - [SolrNet](https://github.com/mausch/SolrNet) - .NET Solr Client. 
    - Last Commit: 11/2019 / Checked: 3/28/2020.

### Scala

  - [Solr Scala Client](https://github.com/takezoe/solr-scala-client) - Scala Solr Client.
    - Last Commit: 3/2020 / Checked: 3/28/2020.
  - [solrs](https://github.com/inoio/solrs) - An async, non-blocking solr client for Java/Scala, providing a query interface like SolrJ.
    - Last Commit: 2/2020 / Checked: 3/28/2020.
  - [Scalikesolr](https://github.com/seratch/scalikesolr) Apache Solr. Client for Scala/Java.
    - Last Commit: 1/2016 / Checked: 3/28/2020.
  - [Solr Play Scala Client](https://github.com/Ramzi-Alqrainy/solr-play-scala-client) - A Scala library in Play framework for indexing and searching documents within an Apache Solr.
    - Last Commit: 6/2017 / Checked: 3/28/2020.
    
### Python

  - [Python Solr Clients](https://cwiki.apache.org/confluence/display/solr/SolPython) - Reference to multiple Python Solr Clients. 
    - Checked: 3/28/2020.
  - [Python:SolrClient](https://github.com/moonlitesolutions/SolrClient) - A simple P{ython library for Solr; built in python3 with support.
    - Last Commit: 11/2019 / Checked: 3/28/2020.
  - [mysolr](http://mysolr.readthedocs.io/en/latest/) - mysolr was born to be a fast and easy-to-use client for Apache Solr’s API and because existing Python clients didn’t fulfill these conditions.
    - Last Commit: 9/2014 / Checked: 3/28/2020.
    
### Ruby

  - [rsolr](https://github.com/rsolr/rsolr) -  A Ruby client for Solr.
    - Last Commit: 1/2020 / Checked: 3/28/2020.
  - [Sunspot](http://sunspot.github.io/) - Solr-powered search for Ruby objects.
    - Last Commit: 3/2020 / Checked: 3/28/2020.
    
### PHP

  - [Solarium](http://www.solarium-project.org/) - A Solr client library for PHP.
    - Last Commit: 3/2020 / Checked: 3/28/2020.
  - [Solr PHP extension](https://pecl.php.net/package/solr) - Allows you to communicate effectively with the Apache Solr Server in PHP.
    - Last Commit: 7/2019 / Checked: 3/28/2020.
    
### Go

  - [go-solr](https://github.com/vanng822/go-solr) - Solr client in Go, core admin, add docs, update, delete, search and more.
    - Last Commit: 2/2020 / Checked: 3/28/2020.
  - [Gora](https://github.com/wirelessregistry/gora) - A simple Solr client for Go.
    - Last Commit: 2/2018 / Checked: 3/28/2020.
  - [Go-Solr](https://github.com/rtt/Go-Solr) - A solr library written in Go. 
    - Old code, author does not recommend using.
    - Checked: 3/28/2020.
    
### Perl

  - [CPAN Apache::Solr](https://metacpan.org/release/Apache-Solr) - Perl Apache Solr.
    - Last Commit: 1/2019 / Checked: 3/28/2020.
    
### Clojure

  - [flux](https://github.com/mwmitchell/flux) - A Clojure based Solr client.
    - Last Commit: 1/2016 / Checked: 3/28/2020.
  - [Solrclj](https://github.com/mlehman/solrclj) - A Clojure client for Apache Solr.
    - Last Commit: 9/2013 / Checked: 3/28/2020.

### Node    

  - [solr-node-client](https://github.com/lbdremy/solr-node-client) - A solr client for node.js - indexing, adding, deleting, committing and searching documents within an Apache Solr installation.
    - Last Commit: 9/2019 / Checked: 3/28/2020.

## Resources

### Documentation

  - [Official Solr Documentation](http://lucene.apache.org/solr/resources.html#documentation)
  - [Official Solr Reference Guide](https://lucene.apache.org/solr/guide/)
  - [Official Solr Community Wiki](https://cwiki.apache.org/confluence/display/solr)

### Books

TODO : Need to get more books, and then order by reading level. 
  - [Enterprise Lucene & Solr](https://www.amazon.com/Enterprise-Lucene-Solr-Lajos-Moczar/dp/0133521761/)
    - Published: 3/2017.
  - [Relevant Search](https://www.amazon.com/Relevant-Search-applications-Solr-Elasticsearch/dp/161729277X)
    - Published: 7/2016.
  - [Apache Solr: A Practical Approach to Enterprise Search](https://www.amazon.com/Apache-Solr-Practical-Approach-Enterprise/dp/1484210719/)
    - Published: 12/2015.
  - [Scaling Big Data with Hadoop and Solr - Second Edition](https://www.amazon.com/Scaling-Big-Data-Hadoop-Solr/dp/1783553391/)
    - Published: 4/2015.
  - [Apache Solr Search Patterns](https://www.amazon.com/Apache-Search-Patterns-Jayant-Kumar/dp/1783981849/)
    - Published: 4/2015.
  - [Apache Solr Enterprise Search Server, 3rd Edition](https://www.amazon.com/Apache-Solr-Enterprise-Search-Server/dp/1782161368/)
    - Published: 2/2015.
  - [Apache Solr: Essentials](https://www.amazon.com/Apache-Solr-Essentials-Andrea-Gazzarini/dp/1784399647/)
    - Published: 2/2015.
  - [Solr Cookbook - Third Edition]
    - Published: 1/2015.
    - The [1st edition](https://www.amazon.com/Apache-Solr-3-1-Cookbook-Rafal/dp/1849512183) was published 7/2011, the [2nd edition](https://www.amazon.com/Apache-Solr-Cookbook-Rafal-Kuc/dp/1782161325/) was published 1/2013.
  - [Scaling Solr](https://www.amazon.com/Scaling-Apache-Hrishikesh-Vijay-Karambelkar/dp/1783981741/)
    - Published: 7/2014.    
  - [Mastering Apache Solr](https://www.amazon.com/Mastering-Apache-Solr-practical-guide/dp/8192784509/)
    - Published: 5/2014.
  - [Solr in Action](https://www.amazon.com/Solr-Action-Trey-Grainger/dp/1617291021)
    - Published: 4/2014.
  - [Einführung in Apache Solr (German)](https://www.amazon.com/Einf%C3%BChrung-Apache-German-Markus-Klose-ebook/dp/B00J5SZP9E)
    - Published: 3/2014.
  - [Apache Solr: Beginner's Guide](https://www.amazon.com/Apache-Beginners-Guide-Alfredo-Serafini/dp/1782162526/)
    - Published: 12/2013.
  - [Instant Apache Solr for Indexing Data How-to](https://www.amazon.com/Instant-Apache-Solr-Indexing-Data/dp/1782164847)
    - Published: 6/2013.
  - [Taming Text](https://www.amazon.com/Taming-Text-Find-Organize-Manipulate/dp/193398838X/)
    - Published: 1/2013.
  - [Apache Solr 5.x: Beginner's Guide](https://www.amazon.com/Apache-Solr-5-x-Beginners-Guide/dp/1785282433/)
    - Published: Unknown.

### Tutorials

  - [Official Solr Quickstart](https://lucene.apache.org/solr/guide/8_5/solr-tutorial.html) 
  - [Solr Tutorial](http://www.solrtutorial.com/)
  - [Solr tutorial](http://yonik.com/solr-tutorial/) - by Yonik Seely, creator of Solr. 
    - Updated: 4/2016.

### Websites

  - [Search Hub](https://lucidworks.com/resources/searchhub/#hub/)
  - [Solr Start](http://www.solr-start.com/)

### Blogs 
  
  - [Solr'n Stuff](http://yonik.com/) - Yonik Seely's Blog. Creator of Solr. 
  - [Open Source Connections](http://opensourceconnections.com/blog/)
  - [Lucidworks Blog](https://lucidworks.com/blog/)
  - [Sematext Blog](https://sematext.com/blog/)


### Docker Images
  - [solr](https://hub.docker.com/_/solr/) - Docker Official Image.
  - (DISCONTINUED) [2degrees/solr4](https://github.com/2degrees/docker-solr4)
  - [search-stack](https://github.com/Appleseed/search-stack) - Appleseed Search Stack Docker composition. Uses Solr, Elasticsearch, MongoDB, Mono, DotNet, ASPNet, NGINX, MySQL, PostgreSQL.
    - Last Commit: 7/2018 / Checked: 3/28/2020.

### Videos
  - TODO 

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
