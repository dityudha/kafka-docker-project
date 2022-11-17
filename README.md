# Getting Started with Kafka-Docker-Project
**Apache Kafka** is a distributed data store optimized for ingesting and processing streaming data in real-time.
</br>
**The Kafka Producer API** allows applications to send streams of data to the Kafka cluster.
</br>
**The Kafka Consumer API** allows applications to read streams of data from the cluster.

## kafka-docker
============

Dockerfile for [Apache Kafka](http://kafka.apache.org/)
</br>
The image is available directly from [Docker Hub](https://hub.docker.com/r/wurstmeister/kafka/)

## Usage

Start a cluster:
</br>
**docker-compose -f docker-compose-expose.yml up -d**
</br>
Stop a cluster:
</br>
**docker-compose stop**

## Connect Kafka Cluster

Connect kafka cluster with kafka tools.
</br>
Download kafka tools:
https://www.kafkatool.com/download.html
</br>
</br>
Configure kafka tools to connect with kafka cluster.
</br>
![1](https://user-images.githubusercontent.com/33762836/202356838-d51adcc7-5c5e-455d-95ab-44c601bd2813.PNG)
![2](https://user-images.githubusercontent.com/33762836/202356870-81497e67-297b-4a74-a99b-4ef228c926bb.PNG)


## Install Library for Producer/Consumer Python App

**pip install kafka-python**


## Run Producer App Example

Example Producer App create with python. 
</br>
To start produce data go to /kafka-producer directory and run:
</br>
**python producer.py** or **py producer.py**
</br>
</br>
![3](https://user-images.githubusercontent.com/33762836/202356872-4d02e8f1-c97d-49c4-afd0-d4a6b5afe0f8.PNG)


## View Data

View produced data with kafka tools.
</br>
</br>
![4](https://user-images.githubusercontent.com/33762836/202356874-0785eddf-c481-4738-a9a1-eaf32bbe7ce2.PNG)
</br>
![5](https://user-images.githubusercontent.com/33762836/202356876-bd5535ed-2df9-40c7-86a9-3825d6aba333.PNG)


## Run Consumer App Example

Example Consumer App create with python.
</br>
To start consume go to /kafka-consumer directory and run:
</br>
**python consumer.py** or **py consumer.py**
</br>
</br>
![6](https://user-images.githubusercontent.com/33762836/202356882-f8dd023f-0188-4096-97c2-b5de04f43367.PNG)


## Tutorial & References

https://towardsdatascience.com/kafka-docker-python-408baf0e1088
</br>
http://wurstmeister.github.io/kafka-docker
