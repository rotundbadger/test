FROM alpine:3.18.4
HEALTHCHECK NONE
RUN apk add --no-cache fortune
RUN useradd monkeyman
USER monkeyman


ENTRYPOINT ["fortune"]
