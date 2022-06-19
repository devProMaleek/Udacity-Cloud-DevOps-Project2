# Cloud DevOps Nano-degree Project 2
Deploy a high-availability web app using CloudFormation

In this project (Udagram App), I deployed web servers for a highly available web app using CloudFormation. The script is divided into eight files for maintenance purpose. I wrote the script that creates and deploys the infrastructure and application for an HighAvailable-WebApp from the ground up. The script begin deploying the networking components followed by servers, security roles and software.



* create.sh : Cloudformation create stack script. 
* update.sh : Cloudformation update stack script.
* destroy.sh : Cloudformation delete stack script.
* bucket-stack.yml : s3 Bucket's CloudFormation yml script.
* bucket-params.json : Project's CloudFormation parameters script.
* network.yml : CloudFormation Network Stack yml script
* network-params.json : CloudFormation Network Stack parameters script
* server.yml : CloudFormation Server Stack yml script
* server-params.json : CloudFormation Server Stack parameters script




URL 
http://udagr-webap-1fl6daoirc8p1-752428503.us-east-1.elb.amazonaws.com/
