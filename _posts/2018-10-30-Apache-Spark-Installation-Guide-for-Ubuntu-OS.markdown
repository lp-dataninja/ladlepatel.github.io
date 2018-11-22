---
title: "Apache Spark Installation on Ubuntu | Blog"
layout: post
date: 2018-10-30 22:48
tag:
- apache
- installation
- bigdata
category: blog
author: Ladle Patel
description: How do you Install Apache Spark on Ubuntu OS

---

INSTALL JAVA
sudo add-apt-repository ppa:webupd8team/java -y

sudo apt-get update

sudo apt-get install oracle-java8-installer

CHECK JAVA VERSION
java -version

CREATE DIRECTORY
mkdir work

CHANGE DIRECTORY
cd work

DOWNLOAD SPARK TAR FILE FROM APACHE MIRRORS.
wget http://redrockdigimark.com/apachemirror/spark/spark-2.1.0/spark-2.1.0-bin-hadoop2.7.tgz

UNZIP  TAR FILE
tar -xzvf spark-2.1.0-bin-hadoop2.7.tgz

RENAME DIRECTORY
mv spark-2.1.0-bin-hadoop2.7 spark

SET THE PATH
vi ~/.bashrc
export SPARK_HOME=/home/ubuntu/work/spark
export PATH=$PATH:$SPARK_HOME/bin

COMPILE THE CHANGES
source ~/.bashrc

START PYSPARK(SPARK WITH PYTHON)
pyspark

START SPARK-SHELL (SPARK WITH SCALA)
spark-shell
