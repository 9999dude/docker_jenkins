```
docker run -ti -p 8080:8080 -p 50000:50000 -v /var/run/docker.sock:/var/run/docker.sock -v <host mapping of jenkins home directory>:/var/jenkins_home --name jenkins -d yellowmence07/docker_jenkins
```
