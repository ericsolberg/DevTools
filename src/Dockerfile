FROM debian:jessie

MAINTAINER Eric Solberg "eric@tinkery.io"

# Update package manager
RUN apt-get update

# Install misc tools/packages
RUN apt-get -y install ca-certificates wget curl zip unzip gzip vim

WORKDIR $DEV_HOME
CMD ["bash"]
