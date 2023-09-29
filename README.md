# wordpress-docker

## build image

```bash
docker build -t <image name>:<tag>
```

# run image
```bash
docker run --name <container name> -p <port to use>:80 <docker image name>:<tag>
```

** Note **
The image file should be use from blob or s3 becuase the file will delete after container / pod restart