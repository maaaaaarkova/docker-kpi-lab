# Docker lab
## Build image
```
docker build . -t maaaaaarkova/kpi.devops.2022:latest
```
## Run container
```
docker run -p 80:80 -d --memory="40m" --cpus=2 maaaaaarkova/kpi.devops.2022:latest
```
