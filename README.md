I have setup a CI/CD pipeline to build and deploy a web app using Groovy code 
1) First I create a 3 ec2 instance on AWS name as server 1 server 2 and server 3 which each of them connected each other with ssh key.
2) Server 1 is the main server where I install jenkins & java and perform all the five stages of CI/CD Workflow of Download, Build, Deploy, Test & Delivery.
3) Server 2 & 3 I named as prod Server & QATomcat server which the url of this server is used in the continous Deployment stage to the Continuous Delivery Stage
4) I used Functional Testing Repo in Testing Stage which is from other resources
   
