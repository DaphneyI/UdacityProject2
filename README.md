# CloudFormation template to Deploy a high available webapp
This project contains two templates for the network and server components separated into the network and server folders respectively as well as their corresponding parameter files.

## Features
1. The sever serves an html file downloaded from an s3 bucket on instance startup.

2. The template uses AWS parameter store to reference the public ip of the host machine that the bastion is configured to accept SSH traffic from, so as to keep the ip address from source control.

For more features refer to the infrastructure diagram in ./UdacityProject2.jpeg


application url : http://server-LB-CDR7J92J6XZ7-312414169.us-west-2.elb.amazonaws.com


