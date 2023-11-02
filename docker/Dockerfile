FROM busybox:1.36
HEALTHCHECK NONE
COPY src/* .
USER busybox

ENTRYPOINT ["cat", "output.txt"]
