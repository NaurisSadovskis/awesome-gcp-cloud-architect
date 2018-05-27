# 01-1 - Cloud SQL

Cloud SQL is Google's fully-managed database service. 

This page focuses primarily on Cloud SQL MySQL offering. Documentation for other supported engine offerings can be found in Cloud SQL [docs](https://cloud.google.com/sql/docs/).

## Timeline

* February 2014 - [Google Cloud SQL now Generally Available with an SLA](https://cloudplatform.googleblog.com/2014/02/google-cloud-sql-now-generally-available.html)
* August 2016 - [Cloud SQL Second Generation performance and feature deep dive](https://cloudplatform.googleblog.com/2016/08/Cloud-SQL-Second-Generation-performance-and-feature-deep-dive.html)
* April 2018 - [Cloud SQL for PostgreSQL now generally available](https://cloudplatform.googleblog.com/2018/04/Cloud-SQL-for-PostgreSQL-now-generally-available-and-ready-for-your-production-workloads.html)


## Resources
NEXT videos (YouTube):
* [Get to know Google Cloud SQL](https://www.youtube.com/watch?v=OV-gak1CUU4)
* [Optimize Cloud SQL performance and availability](https://www.youtube.com/watch?v=rN99XFcAbyo)

General documentation: 

* [**Cloud SQL for MySQL Documentation**](https://cloud.google.com/sql/docs/mysql/)
* [Release Notes](https://cloud.google.com/sql/docs/release-notes)
* [FAQ](https://cloud.google.com/sql/faq)
* [MySQL How-To Guides](https://cloud.google.com/sql/docs/mysql/how-to)
* [Pricing](https://cloud.google.com/sql/pricing)

Operations:
* [MySQL Instance Settings](https://cloud.google.com/sql/docs/mysql/instance-settings)
* [Cloud SQL automatic storage increases (GCP blog)](https://cloudplatform.googleblog.com/2016/09/digging-in-on-Cloud-SQL-automatic-storage-increases.html)
* [Configuring SSL for Instances](https://cloud.google.com/sql/docs/mysql/configure-ssl-instance)
* [Backups](https://cloud.google.com/sql/docs/mysql/backup-recovery/backups)
* [Restores](https://cloud.google.com/sql/docs/mysql/backup-recovery/restoring)
* [Replication Options](https://cloud.google.com/sql/docs/mysql/replication/)
* [Configuring an Instance for High Availability](https://cloud.google.com/sql/docs/mysql/configure-ha)

Books on getting most out of your databases:
* [High Performance MySQL: Optimization, Backups, and Replication, 3rd edition (O'Reilly, 2012)](https://www.amazon.com/High-Performance-MySQL-Optimization-Replication/dp/1449314287)
* [Database Reliability Engineering: Designing and Operating Resilient Database Systems (O'Reilly, 2017)](https://www.amazon.com/Database-Reliability-Engineering-Designing-Operating/dp/1491925949)

## SDK 
```sh
$ gcloud sql
ERROR: (gcloud.sql) Command name argument expected.
Usage: gcloud sql [optional flags] <group | command>
  group may be           backups | databases | flags | instances | operations |
                         ssl-certs | tiers | users
  command may be         connect
```

SDK reference docs can be found [here](https://cloud.google.com/sdk/gcloud/reference/sql/). 


## Summary

Structure: 10

Query complexity: 9.5

Durability: 9.5

Speed: 5

Throughput 3

Cost: 3


