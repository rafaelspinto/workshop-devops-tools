# [Elastic](https://www.elastic.co/products)

The Elastic stack consists of the following components:

* [Elastic Search](https://www.elastic.co/products/elasticsearch) - A fast search engine for analyzing and storing data
* [Logstash](https://www.elastic.co/products/logstash) - A data aggregator that transforms it and sends it to a storage engine
* [Kibana](https://www.elastic.co/products/kibana) - A presentation layer for the data
* [Beats](https://www.elastic.co/products/beats) - Lightweight shippers for data
	* [Filebeat](https://www.elastic.co/products/beats/filebeat) - A shipper for logs


**Note:** 

The Elastic Stack has other components that are missing from the previous list because this workshop has not covered them yet.
 
## Table of Contents

* [Starting Elastic Stack](#starting-elastic-stack)
* [Stopping Elastic Stack](#stopping-elastic-stack)
* [Accessing Kibana](#accessing-kibana)


## Starting Elastic Stack

To start the containers, run the following command on the folder of Elastic:

```shell
docker-compose up -d
```


## Stopping Elastic Stack

To stop the containers, simply run the following command on the Elastic folder:

```shell
docker-compose down
```

## Accessing Kibana

To access the kibana app go to [http://localhost:5601](http://localhost:5601).