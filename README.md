# GoCD setup for workshop

This codebase sets up GoCD containers to compile and publish a
docker image from a sample application


### Commands:

 docker-compose build <br/>
 docker-compose up <br/>

## Note: 
If you face issues with docker go agent throwing this error 'Cannot connect to the Docker daemon.',
please run this command in that Go agent ```chown go:go /var/run/docker.sock```
