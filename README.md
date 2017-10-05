# GoCD setup for workshop

This codebase sets up GoCD containers to compile and publish a
docker image from a sample application

### Commands:

 docker-compose build <br/>
 docker-compose up <br/>

### Post that

 Change DOCKERHUB_USER and DOCKERHUB_PASSWORD in your go-server http://localhost:8153/go/environments/contacts-deployment/show

## Note: 
If you face issues with docker go agent throwing this error 'Cannot connect to the Docker daemon.',
please run this command in that Go agent ```chown go:go /var/run/docker.sock```

