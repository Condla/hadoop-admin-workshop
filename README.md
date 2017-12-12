# Hadoop Admin Workshop

## Agenda

0. 08:30: Prep + Food Ordering
0. 09:00: Introduction and Expectations
0. 09:30: Environment Setup:
0. 10:00 Introduction into Hadoop + Installation
0. 12:30: Lunch break
0. 13:15: Exploring HDFS! (create user, find blocks,...)
0. 13:45: Distributed Systems: Concepts and Components
0. 14:00: Benchmarking + Service Checks
0. 14:30: Secure Cluster
0. 16:30: Outlook. What to do next?
0. 17:00: End + Let's have a drink!

## Prep + Food Ordering

* Join Vienna Admin WhatsApp Group
* Go to mjam.at/blabla and send an email

## Introduction and Expectations
* Interactive Workshop
* Gather experiences of participants
* Gather expectations of participants on whiteboard (?)
* Community Event: Help me to help you; help each other!
* Take pictures and share them!

## Environment Setup
* Did everyone, who wants to participate in the Hadoop Admin Vienna WhatsApp Group give me their number?
* Is the local setup sufficient for the training?
  * SSH client + key in place?
  * SFTP client + key in place?
* Did everyone receive the private key per Email?
* Everyone got assigned a set of 4 AWS machines?
  * https://gist.github.com/Condla/ca7396733451cafa21605da81cf95a5a

## Introduction into Hadoop: Distributed Storage and Processing

* Just a short intro to be sure that everybody is on the same level of knowledge
* Hands On: Install Ambari Server
https://docs.hortonworks.com/HDPDocuments/Ambari-2.6.0.0/bk_ambari-installation/content/ch_Getting_Ready.html
* Hands On: Configure all Ambari Agents
* Hands On: Setup Ambari Server
* Hands On: Install HDP 2.6.3 with 1 Master Node and 3 Worker nodes

## Exploring HDFS
* Hands On: Create a user directory (Linux user + HDFS directory structure)
* Hands On: Load any file into HDFS
* Hands On: Copy Data via Distcp

## Concepts and Components

* Discuss the services and components!
* Get familiar with the concepts: High Availabilty + Scalability (Master/Slave Architecture)
* Check out block of file in HDFS
* Hands On: Adding a second node to the cluster.
* Hands On: Make the installed cluster services highly available.

## Troubleshooting and Service Checks

* Hands On: Run service checks, check health of components
* Hands On: Check log files
* Hands On: Logsearch ?

## Benchmarking

* Discussion: Why Benchmarking?
* Hands On: Terasgen - Generate Random Data
* Hands On: Terasort - Sort Random Data

## Resource Management

* Hands On: YARN applications
* Hands On: YARN Queues

## Secure Cluster

* Install Apache Ranger
* Setup KDC
* Kerberize Cluster
* Setup and configure Apache Knox

## Outlook

* Get into HDP Security (Kerberos + Ranger + Knox)
* Get your hands dirty and get your cluster up and running!
* Maybe, do an additional training 2-3 days training!
* Read a book! Hadoop: The Definitive Guide
* A combination of practical work and studying will get to easily certified:
  * Get certified: https://hortonworks.com/services/training/certification/hdpca-certification/
  * Objectives: https://hortonworks.com/services/training/certification/exam-objectives/#hdpca
