SPRINGBOOT
===

This repo is there just to provide information that if you are going to test any springboot application for any kind of poc in Kubernetes and Docker use mentioned image.

```docker pull prakashsingh08/springboot:v1```   
This iimage can be used in Kubernetes Deployment file to test many scenarios for POC purpose.   

This image contains springboot application java and jmx_exporter.   
This image can be used to test prometheus functionality for exporting metrics.   
jmx_exporter is running on port 5000 and springboot applocation is running on port 8080.
