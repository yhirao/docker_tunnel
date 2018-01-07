FROM ubuntu:14.04.1
RUN apt-get update
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y ssh-client

VOLUME ["/root/.ssh"]

CMD ["ssh"]
