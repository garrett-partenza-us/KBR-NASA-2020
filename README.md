# **KBR Summer 2020 Internship Project**

### Creating a DevSecOps Data-Analytics Dashboard for AWS Services Using ELK stack. 

##### Developers: Garrett Partenza and AJ Ellis

#### Scripts
##### The scripts folder contains the python scripts responsible for moving Amazon serivces data from its origin to an Elasticsearch endpoint. For guardduty.py, clodutrail.py, and codepipeline.py, this occurs in lambda and will need the appropriate deployment package. To develope deployment packages for lambda see https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/. For nmap.py and the inspector scripts however, this occurs in an ec2 instance scheduled by cronjob. 

https://user-images.githubusercontent.com/58012350/89903878-36508980-dbb6-11ea-90a0-9814e2ed4f40.png
