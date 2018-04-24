# Analyzing-syslog-messages-with-Kafka-and-Spark

The goal of this lab is to implement a Spark streaming application that reads from an input topic of syslog messages, determines if the message severity/priority "exceeds" a threshold, and if so, creates and produces a record to an output topic of alerts. 
The list below shows the mapping between number and string:
7 - debug
6 - info
5 - notice
4 - warning, warn
3 - err, error
2 - crit,
1. - alert,
0 - emerg, panic
