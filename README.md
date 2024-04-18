# jenkins-blue-green-deployment

#### Infra setup
```
- Sample application running in multiple EC2 instances and they are grouped into 2 Target Groups one is Blue and another one is Green.
- Both these target groups are attached to an Application Load Balancer(ALB) listening at port 80 with HTTP protocol.
- The setup is a simple web application powered by NGINX
- Refer whole setup https://www.middlewareinventory.com/blog/aws-blue-green-deployment-jenkins/
```
![Uploading blue-green.PNG…]()

#### Jenkins
```
- Setup Jenkins server, install AWS CLI insise the docker container (if jenkins is run as docker).
- Update Jenkinsfile, create index.html file, push changes to git repo.
- Configure Jenkins pipeline job and run build
```


