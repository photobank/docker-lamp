# docker-node
Node environment Dockerfile providing search-client build
```
docker run -p 8080:8080 -it --rm --name search -v "$PWD":/usr/src/app -w /usr/src/app docker-node-4-8080:latest /bin/bash docker-run.sh
```
