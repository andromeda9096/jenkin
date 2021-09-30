# Jenkins

### Install

```
$ curl -sSL https://raw.githubusercontent.com/andromeda9096/jenkin/main/docker-compose.yaml > docker-compose.yml
$ docker-compose up -d

```

### Login web UI

http://ip_host:8080

- password :
```
docker exec jenkins-server cat /var/jenkins_home/secrets/initialAdminPassword
```
### Install Jenkins Plugin

- ansicolor:1.0.0
- blueocean:1.25.0
- kubernetes:1.30.1
