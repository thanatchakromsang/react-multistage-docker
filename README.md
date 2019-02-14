### develop with docker-compose

- `docker-compose up`

### deploy production build image

- `docker build -f Dockerfile -t <image-name>:<version> .`

### run test production build image

- `docker run --rm -p 80:80 <image-name>:<version>`
