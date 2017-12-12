
## on all nodes configure ambari-agents to point to utility
/etc/ambari-agent/conf/ambari-agent.ini

yum reinstall ambari-agent

systemctl restart ambari-agent
## check if client is running
systemctl status ambari-agent

## on utility node
yum install ambari-server
ambari-server setup

* setup as root (customize user account: no)
* install JDK8
* enter advanced database setup
  specify your ambari database credentials
* execute script as suggested

systemctl start ambari-server
# wait and see if you configured it correctly :)
mysql -uambari -pambari -h hostname ambari

netstat -plnt | grep 8080

ssh -i /path/key.pem -L 8080:localhost:8080 ec2-user@mypublicip

ambari-server setup --jdbc-db=mysql \
--jdbc-driver=/usr/share/java/mysql-connector-java.jar

create a gigabyte
time hadoop jar /usr/hdp/2.6.3.0000000/hadoop-mapreduce/hadoop-mapreduce-examples-2.7.3.2.5.5.0-157.jar teragen 10000000 /user/stefan/teragen_data

time hadoop jar /usr/hdp/2.5.5.0-157/hadoop-mapreduce/hadoop-mapreduce-examples-2.7.3.2.5.5.0-157.jar terasort /user/stefan/teragen_data /user/stefan/terasort_out
