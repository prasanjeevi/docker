# docker

## Commands
```
docker info

docker images

docker tag netapiserver:latest prasanjeevi/netapserver:latest
docker push docker.io/prasanjeevi/netapserver:latest


docker run -e
docker run --user=1001
docker run --cap-add MAC_ADMIN

docker ps -a
docker logs -f
```
## Dockerfile
```
ENTRYPOINT [""] # append
CMD [""] # overwrite
