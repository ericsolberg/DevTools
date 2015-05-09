FROM debian:jessie

MAINTAINER Eric Solberg "eric@tinkery.io"

# Update package manager
RUN apt-get update

# Install misc tools/packages
RUN apt-get -y install ca-certificates wget curl zip unzip gzip vim

# Install git
RUN apt-get -y install git

WORKDIR $DEV_HOME
CMD ["bash"]
