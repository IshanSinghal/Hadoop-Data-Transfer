# Hadoop-Data-Transfer

TEAM TASK NO 1

✴️ Whenever client uploads the file ( for ex - f.txt) of size 50MB and the replication is 3. ✴️ Does client takes the entire data to master or does master provides the IP addresses of Datanodes so that client can upload the file to the Datanodes. ✴️ Question: Who is the one uploading the file? ✴️ Answer: Client gets the IP from Master and uploads the file to DataNode. ✴️ Prove this.

TEAM TASK NO 2

✴️ Question: Does client go to master and then read the file on slave via Master or Does Client go to slave directly and read the data? ✴️ Answer: Client goes to slave directly and reads the data stored on slave. ✴️ Prove this.

https://www.linkedin.com/pulse/hadoop-breaking-myths-proof-ishan-singhal/

Many people believe that the NameNode is involved in data transfer between the Client and DataNodes.

Here's an article showing how the NameNode is involved only in providing info about the DataNodes and files. Data transfers/read happens directly between Client and DataNodes.
