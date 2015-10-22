FROM alpine:edge

ENV ALPINE_VERSION edge

COPY files /
RUN  chmod +x /usr/local/bin/apk-install
RUN apk-install curl ca-certificates
