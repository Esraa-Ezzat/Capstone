Project 5 - Cloud DevOps Engineer Capstone Project
     Project Tasks:
Working in AWS
Using Jenkins to implement Continuous Integration and Continuous Deployment
Building pipelines
Working with CloudFormation to deploy clusters
Building Kubernetes clusters
Building Docker containers in pipelines
                               about project :
     1- creating github repo
     2- project consisits of two pipelines:
        pipeline 1 : (cluster creation)
              authenticate into aws ---------> create the kubernetes cluster -------> create a configuration file for the cluster
        pipeline 2 : ( containers deployment)
               Linting HTML -----> build the Docker image ------> upload image to docker -----> set current kubectl to the cluster ----> create a replication controller blue pod ------> create a replication controller green pod -----> create the service in kubernetes cluster ----> wait until the user approved ---> update the service to redirect to green 
