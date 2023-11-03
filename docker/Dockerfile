FROM alpine:3.18.4
HEALTHCHECK NONE
RUN apk add fortune
COPY ./docker/src/* /
USER monkeyman


ENTRYPOINT ["fortune"]
