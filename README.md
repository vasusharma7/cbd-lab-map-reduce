# cbd-lab-map-reduce

 - Demonstration of Map Reduce on Hadoop Cluster for Counting Words in a text file.
 - Steps for generating and running on hadoop cluster
     - mvn package
     - hdfs dfs -mkdir /data
     - hdfs dfs -put ./words.txt /data
     - hadoop jar target/hadoop-word-count-0.1.0.jar /data/words.txt /r_output
     - hdfs dfs -cat /r_output/part-00000
 - The input files and results of map-reduce algorithm are stored in results folder.
