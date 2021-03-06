# README - Install Hadoop Spark Ubuntu 18.04 #

This README document steps necessary to get your application up and running.


### How to install? ###

1. Open Ubuntu 18.04 (LTS) x64 Terminal or access your cloud with ssh, using the command below:

	`ssh <user>@<ip_number>`

	**Attention: Never use "root" user!**

2. Execute the command to clone this repository:

	`sudo apt install git`

	`git clone https://github.com/marcelomdevasconcellos/Install-Hadoop-Spark-Ubuntu-18.04.git`

3. Execute the command:

	`cd Install-Hadoop-Spark-Ubuntu-18.04`
	
	`source install_hadoop_spark_ubuntu.sh`


### What will be installed? ###

* Java 8.0.252
* Hadoop 3.2.1
* Spark 3.0.0
* Mongodb
* Mongodb Compass Community
* Mysql
* FTP


### Credits: ###

* https://dev.to/awwsmm/installing-and-running-hadoop-and-spark-on-ubuntu-18-393h
* https://www.digitalocean.com/community/tutorials/how-to-install-mongodb-on-ubuntu-18-04-pt
* https://towardsdatascience.com/installing-pyspark-with-java-8-on-ubuntu-18-04-6a9dea915b5b
* https://www.digitalocean.com/community/tutorials/how-to-set-up-vsftpd-for-a-user-s-directory-on-ubuntu-18-04
