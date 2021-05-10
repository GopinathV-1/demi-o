# ElasticSearch vs Lucene vs Solr 
You may think that what these names actually refer to and why they are used? 
, which is the best among them? All your questions will be cleared here. Let dive into it. 
The above-mentioned ElasticSearch, Lucene and Solr are **[full-text search engines](https://en.wikipedia.org/wiki/Full-text_search)**.
### what is full_text search?
In short, full-text search refers to techniques for searching a single computer-stored document or a collection in a full-text database.

### why full_text search?
we also have sequential scanning method for searching full_text data, but the catch here is, 
the sequential scanning method is slow in searching unstructured data, whereas the full_text search performs well in searching both structured and unstructured data. 

We might think **how** full_text search performs well for unstructered data? 
A part of the information in the unstructured data is extracted, reorganized to make it have a 
certain structure, and then the data with a certain structure is searched to achieve a 
relatively fast search. 

## Lucene 
Lucene is an open-source search engine fully developed in java. It searches by index so, 
Search speed is high. It is an API that can be easily used to add search functionality to
your application. Simple API provides powerful features and high scalable performances. It was
developed by Apache Software Foundation.

## Solr 
Solr is an open-source search platform developed in java. It performs operations like
Indexing, Querying, Mapping, Ranking the outcome. It uses the Lucene Java search library at
its core for full-text indexing and search. It also searches by index. It was
developed by Apache Software Foundation.

## Elasticsearch
Elasticsearch is a distributed, free and open search and analytics engine for all types of
data. It is built on Apache Lucene. It excels at full-text search. It provides a very high
speed in search and scalability in performance. It is used for application search, website
search, enterprise search, many more. Logstash, one of the core products of the Elastic Stack,
is used to aggregate and process data and send it to Elasticsearch. Kibana is a data 
visualization and management tool for Elasticsearch that provides real-time histograms, line 
graphs, pie charts, and maps. 

## Summary 
In a nutshell, When we compare all three search engines both Elacticsearch and Solr
predominantly overtakes in speed, performance and support provided basis. When we look into 
Elasticsearch and Solr, Solr has a large active development and user community, it has    
dominated the search field many years. Although Elasticsearch is young, it also has some
advantages of its own. lasticsearch is built on more modern principles, is aimed at more
modern use cases, and is built to make it easier to handle large indexes and high query rates.
so over Lucene and solr we can prefer Elasticsearch as a full_text search engine.
The notable advantages of Elasticseach engine are,
* Elasticsearch is fast.
* Elasticsearch is distributed by nature.
* Elasticsearch comes with a wide set of features.
* The Elastic Stack simplifies data ingest, visualization, and reporting.

#### References
http://www.lucenetutorial.com/basic-concepts.html
https://www.theserverside.com/definition/Apache-Solr
https://www.elastic.co/what-is/elasticsearch
https://www.hcltech.com/blogs/elasticsearch-vs-solr
https://anytxt.net/how-to-choose-a-full-text-search-engine/
