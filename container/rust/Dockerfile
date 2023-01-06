FROM ubuntu:22.04

RUN apt-get update
RUN apt-get install sudo

# ENTRYPOINT ["tail", "-f", "/dev/null"]
CMD exec /bin/bash -c "trap : TERM INT; sleep infinity & wait"