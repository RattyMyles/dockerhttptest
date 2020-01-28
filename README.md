# Docker http test

### Purpose of this project?
Small docker container that shows uname -a when you send it a http request. Usefull for testing clusters and AWS.

```
docker run -d -p 80:8000 rattymyles/smallhttptest

```

Created a small html file with the command of "uname -a" and stored it in index.html. Also listening on port 8000 (Don't use 1-1024 of known registered ports) and run it in foreground "-f" && wait
