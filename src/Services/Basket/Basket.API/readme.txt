docker pull redis
docker run -d -p 6379:6379 --name aspnetrun-redis redis
docker logs -f aspnetrun-redis
docker exec -it aspnetrun-redis /bin/bash
#redis-cli
-- you can then use get/set/delete command in redis-cli environment
docker ps
docker stop container_id
docker rm container_id
-- add portainer
