# docker-alpine-curl-ssh
Stock alpine docker image with curl + ssh included.

```
FROM alpine:3.8

RUN apk add --no-cache curl openssh
```
