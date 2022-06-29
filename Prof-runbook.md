
## JJTech GCP CICD Project Runbook

### SonarQube Credentials (Will be using in Maven)
```
Token: jjtech-cicd-java-project: 249b87285f1c4e2032590107183c24b75aa9c1bb
```
```
##JJTech-CICD-Java-Project: 
mvn sonar:sonar \
  -Dsonar.host.url=http://34.125.111.93:9000 \
  -Dsonar.login=249b87285f1c4e2032590107183c24b75aa9c1bb
```

### Nexus Credentials
```
username: admin
password: admin
ip address: 34.121.187.165
```


### Maven Credentials
```
username: 
password: 
ip address: 34.134.59.227
```


### Ansible Credentials
```

```


### Jenkins Credentials
```
username: admin
password: admin
ip address: 34.134.59.227
```


### Github Credentials
```
webhook: http://34.134.59.227:8080/github-webhook/
```
