[DockerHub](https://hub.docker.com/repository/docker/jonbri/playwright-extend/general)

```sh
docker build -t jonbri/playwright-extend .
echo "your-password-here" | docker login --username jonbri --password-stdin
docker push jonbri/playwright-extend
```
