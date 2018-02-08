## Docker

- delete all containers

```bash
docker rm $(docker ps -a -q)
```

- delete all images

```bash
docker rmi $(docker images -q)
```
