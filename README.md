# YangDocker

自助搭建的 hadoop + spark + kafka + zookeeper + storm + hbase + hive + flume + mysql + redis 集群，一主两从。

## 操作指南

先将项目 clone 到本地，然后进入目录，然后运行：

```bash
bash ./image.sh
```

然后等待，构建所有的相关镜像。

## 操作系统

ubuntu:16.04

## 工具包

Hadoop 2.6：[下载地址](http://archive.apache.org/dist/hadoop/common/hadoop-2.6.0/hadoop-2.6.0.tar.gz)

Hive 1.2.2：[下载地址](http://mirror.bit.edu.cn/apache/hive/hive-1.2.2/apache-hive-1.2.2-bin.tar.gz)

kafka 2.11：[下载地址](http://mirrors.tuna.tsinghua.edu.cn/apache/kafka/0.10.2.1/kafka_2.11-0.10.2.1.tgz)

JDK 1.8：[下载地址](http://download.oracle.com/otn-pub/java/jdk/8u172-b11/a58eab1ec242421181065cdc37240b08/jdk-8u172-linux-x64.tar.gz)

scala 2.11.4：[下载地址](https://downloads.lightbend.com/scala/2.11.4/scala-2.11.4.tgz)

spark 1.6.0：[下载地址](https://archive.apache.org/dist/spark/spark-1.6.0/spark-1.6.0-bin-hadoop2.6.tgz)

zookeeper 3.4.5：[下载地址](http://archive.apache.org/dist/zookeeper/zookeeper-3.4.5/zookeeper-3.4.5.tar.gz)

hbase 0.98.6：[下载地址](http://archive.apache.org/dist/hbase/hbase-0.98.6/hbase-0.98.6-hadoop2-bin.tar.gz)

flume 1.6.0：[下载地址](http://archive.apache.org/dist/flume/1.6.0/apache-flume-1.6.0-bin.tar.gz)

mysql-connector 5.1.41：[下载地址](http://dev.mysql.com/get/Downloads/MySQL-5.1/mysql-5.1.41.tar.gz)

redis 2.8.3：[下载地址](http://download.redis.io/releases/redis-2.8.3.tar.gz)

storm 0.9.3：[下载地址](https://archive.apache.org/dist/storm/apache-storm-0.9.3/apache-storm-0.9.3.tar.gz)

## 注意

因为所有的环境/安装包都是临时下载的，所以构建过程速度较慢，镜像较大。

## 其他

欢迎 issue。

## 参考

1. [利用Docker搭建大数据处理集群](https://blog.csdn.net/iigeoxiaoyang/article/details/53020066)
