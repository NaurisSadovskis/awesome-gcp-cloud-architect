# 1.2 - Cloud Datastore

Cloud Datastore is a highly-scalable NoSQL database.

## Introduction
### Design specifics
* **Data locality**: Datastore is designed in a way where you can choose which documents live near which other documents by putting them in the same entity group. Queries inside a single entity group are strongly consistent.
* **Result-set query scale**: Datastore uses indexing to accomplish just this, so that if your query has 10 matches, it’ll take the same amount of time regardless of whether you have 1 GB or 1 PB of e-mail data.
* **Automatic replication**: Any data written should be automatically replicated to many different physical servers

## Timeline
* May 2013 - [Get started with Google Cloud Datastore - a fast, powerful, NoSQL database](https://cloudplatform.googleblog.com/2013/05/get-started-with-google-cloud-datastore-nosql-database.html)
* February 2018 - [Fully managed export and import with Cloud Datastore now generally available](https://cloudplatform.googleblog.com/2018/02/fully-managed-export-and-import-with-Cloud-Datastore-now-generally-available.html)

## Resources
NEXT videos (YouTube):
* [Cloud Datastore 101: Overview of Google's scalable NoSQL document database](https://www.youtube.com/watch?v=uZDk0NZGqHs)
* [Building scalable apps with Cloud Datastore](https://www.youtube.com/watch?v=0EIqacNVuAo)

General documentation: 
* [**Cloud Datastore Documentation**](https://cloud.google.com/datastore/docs/)
* [Concepts](https://cloud.google.com/datastore/docs/concepts)
* [Release Notes](https://cloud.google.com/datastore/release-notes)
* [Best Practices](https://cloud.google.com/datastore/docs/best-practices)
* [Datastore How-To Guides](https://cloud.google.com/datastore/docs/how-to)
* [Pricing](https://cloud.google.com/datastore/pricing)

Operations:
* [Exporting and Importing Entities](https://cloud.google.com/datastore/docs/export-import-entities)

Books on understanding NoSQL:
* [Seven Databases in Seven Weeks: A Guide to Modern Databases and the NoSQL Movement (Pragmatic Bookshelf, 2012)](https://www.amazon.com/Seven-Databases-Weeks-Modern-Movement/dp/1934356921/) (chapters on CouchDB and MongoDB)
* [NoSQL For Mere Mortals (Addison-Wesley Professional, 2015)](https://www.amazon.com/NoSQL-Mere-Mortals-Dan-Sullivan/dp/0134023218/)

## SDK 
```sh
$ gcloud datastore
ERROR: (gcloud.datastore) Command name argument expected.
Usage: gcloud datastore [optional flags] <command>
  command may be         cleanup-indexes | create-indexes
```

SDK reference docs can be found [here](https://cloud.google.com/sdk/gcloud/reference/datastore/. 

## Summary
Structure: 5

Query complexity: 5

Durability: 10

Speed: 4.5

Throughput: 10

Cost: 7
