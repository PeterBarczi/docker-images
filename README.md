# Rocky WEB APP

Simple Docker image running _Nginx_ web server with _Rocky_ related web pages. There is a CICD Pipeline in place which is responsible for generating Docker images in case that content of web changes.  The requested part of Rocky series can be specified by Tags:

* `latest`, `4`
* `3`
* `2`
* `1`

## Run the Container from Image

```
docker container run -t petyb/rocky:TAG
```
