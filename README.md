# WordCount-docker
A demo of Hadoop wordcount encapsulated with docker
# Usage
 1. docker pull dylone/wc-demo 
 2. docker run -it dylone/wc-demo /bin/bash
 3. execute `/usr/sbin/sshd -D &` in the shell of the container to start sshd.
 4. execute `/root/hadoop/hadoop-3.1.4/sbin-start-all.sh` in the shell of the container to start hdfs.
 5. then You can refer to it ![here](https://hadoop.apache.org/docs/stable/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html) to complete WordCount.
 
 based on:Hadoop 3.1.4，jdk1.8
