# 1.4 - Cloud Bigtable

Cloud Bigtable is Google's NoSQL Big Data database service.

## Timeline
* May 2015 - [Announcing Google Cloud Bigtable: The same database that powers Google Search, Gmail and Analytics is now available on Google Cloud Platform](https://cloudplatform.googleblog.com/2015/05/introducing-Google-Cloud-Bigtable.html)
* August 2016 - [Google Cloud Bigtable is generally available for petabyte-scale NoSQL workloads](https://cloudplatform.googleblog.com/2016/08/Google-Cloud-Bigtable-is-generally-available-for-petabyte-scale-NoSQL-workloads.html)
* November 2016 - [Bigtable paper earns the SIGOPS 2016 Hall of Fame Award](https://cloudplatform.googleblog.com/2016/11/Bigtable-paper-earns-the-SIGOPS-2016-Hall-of-Fame-Award.html)
* May 2018 - [Regional replication for Cloud Bigtable now in beta](https://cloudplatform.googleblog.com/2018/05/regional-replication-for-cloud-bigtable.html)

## Resources
NEXT videos (YouTube):
* [Bigtable in action](https://www.youtube.com/watch?v=KaRbKdMInuc)
* [Bigtable, BigQuery, and iCharts for ingesting and visualizing data at scale](https://www.youtube.com/watch?v=2HUB4uu7K2k)
* [Case Study: Processing data at scale with Google Cloud Bigtable, Dataflow, and Dataproc](https://www.youtube.com/watch?v=dcSeF51HP3U)

Other:
* [Media: Articles, Videos, and Podcasts](https://cloud.google.com/bigtable/docs/media)

General documentation: 
* [**Cloud Bigtable Documentation**](https://cloud.google.com/bigtable/docs/)
* [Concepts](https://cloud.google.com/bigtable/docs/concepts)
* [Release Notes](https://cloud.google.com/bigtable/docs/release-notes)
* [Bigtable How-To Guides](https://cloud.google.com/bigtable/docs/how-to)
* [Pricing](https://cloud.google.com/bigtable/pricing)
* [Whitepaper: Bigtable: A Distributed Storage System for Structured Data](https://ai.google/research/pubs/pub27898)

Books on understanding planet-size databases:
* [HBase: The Definitive Guide: Random Access to Your Planet-Size Data (O'Reilly, 2018)](https://www.amazon.com/HBase-Definitive-Random-Access-Planet-Size/dp/1492024260/ref=sr_1_3?ie=UTF8&qid=1527614127&sr=8-3&keywords=hbase)

## SDK 
* [Installing the GCP SDK for Cloud Bigtable (includes cbt tool)](https://cloud.google.com/bigtable/docs/installing-cloud-sdk)
```sh
$ gcloud beta bigtable
ERROR: (gcloud.beta.bigtable) Command name argument expected.
Usage: gcloud beta bigtable [optional flags] <group>
  group may be           app-profiles | clusters | instances
```

## Summary
Structure: 1

Query complexity: 1

Durability: 9.5

Speed: 10

Throughput: 10

Cost: 9