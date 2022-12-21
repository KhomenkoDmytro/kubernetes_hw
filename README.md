docker build . -t dmytrokhomenk0/docker_hw
docker run -p 49160:80 -m 100m --cpus="2" -d dmytrokhomenk0/docker_hw
