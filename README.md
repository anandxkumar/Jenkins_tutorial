# Jenkins_tutorial

Use the following commands to run jenkins using docker locally
- `$ sudo service docker start`
- `$ docker run -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts-jdk11`
- `https://localhost:8080`
