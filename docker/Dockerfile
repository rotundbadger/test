FROM alpine:1.36
HEALTHCHECK NONE
RUN apk add fortune
COPY ./docker/src/* /
USER monkeyman


ENTRYPOINT ["fortune"]
