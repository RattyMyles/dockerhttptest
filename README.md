# Docker http test

### Purpose of this project?
A small docker container to run on AWS for testing purposes.

```
docker run -d -p 80:8000 rattymyles/smallhttptest

```

Created a small html file with the command of "uname -a" and stored it in index.html. Also listening on port 8000 (Don't use 1-1024 of known registered ports) and run it in foreground "-f" && wait
