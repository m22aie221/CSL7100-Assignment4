 start-dfs.sh
 hdfs dfs -mkdir -p /user/rajesh/spam_data
 hdfs dfs -put /home/rajesh/CSL7100-Assignment4/Part1/Q1_Spam/spambase.data /user/rajesh/spam_data/
 hdfs dfs -ls /user/rajesh/spam_data