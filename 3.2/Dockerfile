FROM alpine:3.2

ENV ALPINE_VERSION 3.2

COPY files /
RUN  chmod +x /usr/local/bin/apk-install
RUN apk-install curl ca-certificates
