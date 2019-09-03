# apache-livy
Apache Livy is an open source REST interface for interacting with Apache Spark from anywhere.
  - Have long running Spark Contexts that can be used for multiple Spark jobs, by multiple clients
  - Share cached RDDs or Dataframes across multiple jobs and clients
  - Multiple Spark Contexts can be managed simultaneously, and the Spark Contexts run on the cluster (YARN/Mesos) instead of the Livy Server, for good fault tolerance and concurrency
  - Jobs can be submitted as precompiled jars, snippets of code or via java/scala client API
  - Ensure security via secure authenticated communication

<p align="center">
  <img src="https://livy.incubator.apache.org/assets/images/livy-architecture.png" height=70% width=70%/>
</p>


Scenarios livy fault tolerance:

<p align="center">
  <img src="https://github.com/uuhnaut69/apache-livy/blob/master/img.png" height=70% width=70%/>
</p>
