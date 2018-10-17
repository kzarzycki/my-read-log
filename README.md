# my-read-log
Data engineering, programming and other news, articles I read related to my profession and interests. 

# 2018-10-17
* Pretty simple tutorial how to build home-grown smart-home alerting system using Pi, KSQL, H2O, Pushbullet and Hass.io.
  
  https://medium.com/@simon.aubury/machine-learning-kafka-ksql-stream-processing-bug-me-when-ive-left-the-heater-on-bd47540cd1e8
  
* Conda libraries come preconfigured, optimized, in contrast to pip libraries. Wow, didn't know that.

  https://towardsdatascience.com/stop-installing-tensorflow-using-pip-for-performance-sake-5854f9d9eb0c
  
  
* I always thought it would be very useful to have node.js based big data processing system. Many people are JS only and could leverage that. Still haven't seen one, but this tutorial shows at least how to quickly stream files to node.js processor.

  https://itnext.io/using-node-js-to-read-really-really-large-files-pt-1-d2057fe76b33
  
* Mm, nice. Offloading HBase deep/cold storage to S3 (or any cloud storage?). Doesn't look straightforward, as manual has 50 pages.

  https://aws.amazon.com/blogs/big-data/migrate-to-apache-hbase-on-amazon-s3-on-amazon-emr-guidelines-and-best-practices/
  
* Pulsar: Another system that can offload deep/cold storage to S3 (or any cloud storage?). I wonder when Kafka will finally support such approach.

  https://streaml.io/blog/configuring-apache-pulsar-tiered-storage-with-amazon-s3
  
* How to run Zookeeper on really large scale? Twitter shares their approach. Learned about Zookeeper local sessions, more about Observers and operations. I haven't had yet such use case. I'm curious how embedded approaches like https://atomix.io/ (based on Raft) perform in such use cases, because it's always a pain to have an additional service like ZK.

  https://blog.twitter.com/engineering/en_us/topics/infrastructure/2018/zookeeper-at-twitter.html

# 2018-10-16
* Why-across-time provenance. On the subject of debugability of distributed systems. This kind of feature could be implemented platform-wide in things like Atlas.

  http://delivery.acm.org/10.1145/3270000/3267839/p333-Whittaker.pdf
# 2018-10-15

* Pretty good comparison of performance and concurrency of Hive, Impala and GC BigQuery. I'm curious how Presto would perform here. Unfortunately missing open-sourcing the benchmark to make it repeatable by others (even without the company private queries).

  https://medium.com/@TechKing/benchmarking-google-bigquery-at-scale-13e1e85f3bec



# Ending note
This is just an experiment. I'm not sure if I will systematically put stuff on that list. 
And of course I just started the list today (2018-10-15) and I don't even think about putting here what I already read in my life :) 


## Kudos
Kudos:
* for an idea to https://github.com/sderosiaux and his list https://github.com/sderosiaux/every-single-day-i-tldr. 
* for a great weekly newspaper https://dataengweekly.com by (Joe Crobak)[https://www.linkedin.com/in/joecrobak]
