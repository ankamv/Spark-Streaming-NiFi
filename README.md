# Quick Start

```
$ git clone https://github.com/ankamv/Spark-Streaming-NiFi.git
$ cd Spark-Streaming-NiFi
$ curl https://bintray.com/sbt/rpm/rpm | sudo tee /etc/yum.repos.d/bintray-sbt-rpm.repo
$ sudo yum install sbt
$ sbt assembly

- Start the spark streaming job

```
$ spark-submit target/scala-2.10/Spark-Streaming-NiFi-assembly-1.0.jar
```

# references
- https://blogs.apache.org/nifi/entry/stream_processing_nifi_and_spark
- http://spark.apache.org/docs/latest/streaming-programming-guide.html
