# docker-dev
My Docker environment for development projects

I download this repository to my local projects to give me a starting setup for development docker.

The docker-compose file has lables in it that are used by Traefik 2 which I use a frontend proxy for all my projects so I don't have to jugle ports.

To use, run:
```angular2html
wget https://github.com/adear11/docker-dev/archive/master.zip && unzip master.zip && mv docker-dev-master/* . && rmdir docker-dev-master && rm master.zip
```