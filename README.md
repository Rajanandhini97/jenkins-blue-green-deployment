# jenkins-blue-green-deployment

#### Infra setup
```
- Sample application running in multiple EC2 instances and they are grouped into 2 Target Groups one is Blue and another one is Green.
- Both these target groups are attached to an Application Load Balancer(ALB) listening at port 80 with HTTP protocol.
- The setup is a simple web application powered by NGINX
- Refer whole setup https://www.middlewareinventory.com/blog/aws-blue-green-deployment-jenkins/
```
<img width="652" alt="blue-green" src="https://github.com/Rajanandhini97/jenkins-blue-green-deployment/assets/72840836/5b6a1f50-46bf-4320-b549-3a7f16d3307f">

#### Jenkins
```
- Setup Jenkins server, install AWS CLI insise the docker container (if jenkins is run as docker).
- Update Jenkinsfile, create index.html file, push changes to git repo.
- Configure Jenkins pipeline job and run build
```


