FROM alpine:3.18.4
ARG USER=monkeyman
ENV HOME /home/$USER
HEALTHCHECK NONE
RUN apk add --no-cache fortune
RUN adduser -D $USER
USER $USER
WORKDIR $HOME
ENTRYPOINT ["fortune"]
