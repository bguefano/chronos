# Chronos UI
## The front-end companion to the back-end scheduler.
## Build
```
docker build -t chronos-ui .
```
## Run
```
docker run -e "CHRONOSAPI_URL=http://<host:port>/v1" -d -p 8080:80 chronos-ui
```
