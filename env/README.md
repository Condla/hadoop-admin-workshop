# Environment Setup for Hadoop Admin Workshop

For the free Hadoop Admin Workship I'm giving, I used this part to setup the environment for all participants.
This will get you through the boring repetitive sysadmin parts, such as fullfilling all the prerequisites required to install Hadoop and installing a minimally operating MySQL database server as well as installing and configuring ambari agents on all nodes.

What it does in Detail:
* Spin up AWS instances based on the config file you provide  (```./vars/ec2.yml```)
* Bootstrap all nodes
* Install Mysql Server
* Install Ambari Agents

For the workshop it is required for the participants to install the ambari-server manually and create their cluster manually.
Automating this part would usually be done with Ambari Blueprints.

## Prerequisites

* Clone this repository and change to the env directory
* Make sure you configure the ./vars/ec2.yml file based on your environment
* Have a look at all the other variables in the vars directory and adjust them as you desire
* Have awscli installed
  "pip install awscli"
* Run ```aws configure``` and enter your AWS environment details


## Installation

* Execute the script:

  ```
  ./setup.sh
  ```
