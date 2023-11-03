FROM busybox:1.36
HEALTHCHECK NONE
COPY ./docker/src/* /
USER busybox


ENTRYPOINT ["cat", "output.txt"]
