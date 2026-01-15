## build the image

docker build -t node-js .

## run environment

- docker run --rm -p 8888:8888 -v "$PWD":/home/jovyan/work node-js
- docker run --rm -p 8888:8888 -v "/tmp/nodejs/volumes":/home/jovyan/work node-js
- docker run --rm -p 8888:8888 node-js
