Sadewa: Stream Kafka to File Storage.
======

This Project is to stream twitter timeline and parse it to Kafka Fronting. 

Python Library Installation
------------
The easiest way to install the latest version
is by using pip/easy_install to pull it from PyPI:

    pip install kafka-python
    pip install pyspark

Download Spark Streaming
----
wget http://central.maven.org/maven2/org/apache/spark/spark-streaming-kafka_2.10/1.6.3/spark-streaming-kafka_2.10-1.6.3.jar

Start Service
----
spark-submit --packages org.apache.spark:spark-streaming-kafka-0-8_2.11:2.2.0 --jars /home/syarifhidayatullah/spark-streaming-kafka_2.10-1.6.3.jar spark_direct_based.py localhost:9092 hello-kafk
