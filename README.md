# EC2-Docker-Demo

This is a basic flask app docker container.

When the container is running, it will be attached to port 80 of the machine, go to: http://(aws host ip):80 to view the site.

Flask, by default, is running on port 5000 of the container, but the docker-compose binds host port 80 to container port 5000.

You can execute this locally but as following the youtube video this will be done through AWS Ec2 Instance connect

Youtube video - 
