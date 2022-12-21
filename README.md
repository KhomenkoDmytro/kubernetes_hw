```
docker build . -t dmytrokhomenko/docker_hw
docker run -p 49160:80 -m 100m --cpus="2" -d dmytrokhomenko/docker_hw
```
