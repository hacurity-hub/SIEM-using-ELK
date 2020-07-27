# SIEM-using-ELK-stack-7.8

#Setting up a SIEM is really simple using an opensource ELK stack.

#Elasticsearc --> Stores the logs
#Logstash --> Parses / Filters the logs
#Kibana --> Visualisation of logs

#The work flow is quite different from the order of the ELK like,
  Agent --> Logstash --> Elasticsearch --> Kibana.
 
#Agent is the log shipper that ships the logs from the servers, hosts, security devices and network devices to logstash.
	There are different agents for different OS platforms and separate agents to send system(inbuilt logs) logs and specific application logs.
