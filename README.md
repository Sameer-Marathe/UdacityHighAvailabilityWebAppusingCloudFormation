### Project Title - Deploy a high-availability web app using CloudFormation
This repository is implementation of second project in Udacity CloudDevOps-Nanodegree. More details (from udacity) are as follows:

As your final project, you'll be faced with a real scenario.

Creating this project will give you the hands-on experience you need to confidently talk about infrastructure as code. So, for that reason, we have chosen a realistic scenario where you deploy an application (Apache Web Server) and you also pick up code (JavaScript and HTML) from S3 Storage and deploy it in the appropriate folder on the web server.

In this project, you’ll deploy web servers for a highly available web app using CloudFormation. You will write the code that creates and deploys the infrastructure and application for an Instagram-like app from the ground up. You will begin with deploying the networking components, followed by servers, security roles and software. 

There will be two parts to this project:

- You'll first develop a diagram that you can present as part of your portfolio and as a visual aid to understand the CloudFormation - script.
- The second part is to interpret the instructions as well as your own diagram and create a matching CloudFormation script.

### To create Stack 
```
./create.sh infra infrastructure.yml infra-parameters.json
./create.sh temps server-infra.yml server-parameters.json
```


### To update stack 

```
./create.sh infra infrastructure.yml infra-parameters.json
./create.sh temps server-infra.yml server-parameters.json
```

### to delete stack
```
./delete.sh infra infrastructure.yml infra-parameters.json
./delete.sh temps server-infra.yml server-parameters.json
```
