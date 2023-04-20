## End to End MAchine Learning Project

1. Docker Build checked
2. Github Workflow
3. Iam User In AWS

## Docker Setup In EC2 commands to be Executed

#optinal

sudo apt-get update -y         #entire packages will be installed and indexed properly

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh  #installing docker based libraries

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

## Configure EC2 as self-hosted runner:

## Setup github secrets:

AWS_ACCESS_KEY_ID= given in excel

AWS_SECRET_ACCESS_KEY= given in excel

AWS_REGION = us-east-2

AWS_ECR_LOGIN_URI = demo>>  355128487270.dkr.ecr.us-east-2.amazonaws.com

ECR_REPOSITORY_NAME = studentperformance
