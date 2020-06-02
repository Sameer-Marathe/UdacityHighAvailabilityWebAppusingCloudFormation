### Project Title - Deploy a high-availability web app using CloudFormation
To create Stack 
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
### Web-App link
http://temps-webap-27ps5sfw84rd-454804646.us-west-2.elb.amazonaws.com/
