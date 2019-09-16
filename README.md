# GitHub Actions demo

This repo demonstrates a workflow for a Docker container-based Node.js web application.
The [workflow](https://github.com/bbq-beets/demo/blob/master/.github/workflows/build-and-deploy.yml):

* Builds a Docker container image and pushes it to GitHub Package Registry
* Deploys the container to Amazon Elastic Container Service ([here](http://ec2co-ecsel-zcdur7dfi3go-65794761.us-east-2.elb.amazonaws.com/)).
* Deploys the container to Azure Web App for Containers ([here](https://dastahel-dreamlifter-deploy.azurewebsites.net/)).
* Deploys the container to Google Kubernetes Engine ([here](http://35.192.223.50/)).
   
  
