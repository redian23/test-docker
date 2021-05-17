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
localhost:8000
```
``or``
```
docker inspect testing_nginx_1 |grep 'Gateway' 
{ip}:8000
```
``or``
```
ip a | grep inet
local_ip:8000
```
