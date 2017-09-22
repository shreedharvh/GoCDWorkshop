# GoCD setup for workshop

docker-compose build
docker-compose up

Note: if you see an error 'Cannot connect to the Docker daemon.' in a pipeline,
please run this command in that Go agent 'chown go:go /var/run/docker.sock'
