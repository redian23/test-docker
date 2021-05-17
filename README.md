# test-docker

1. Docker Engine & Docker Compose install 

2. Unboxing
```
git clone https://github.com/redian23/test-docker.git -b main test
cd test/
docker-compose build
docker-compose up -d 
```
3. open page 
```
localhost:port
```
``or``
```
docker inspect testing_nginx_1 |grep 'Gateway' 
{ip}:port
```
``or``
```
ip a | grep docker
docker_ip:{port}
```
On `docker_ip/` page open, but if press 'F5' or "reload page" page is close. 
