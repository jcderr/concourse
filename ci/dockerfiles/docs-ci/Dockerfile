FROM rubinius/docker

RUN locale-gen en_US.UTF-8
RUN dpkg-reconfigure locales
ENV LANG en_US.UTF-8
ENV LC_ALL en_US.UTF-8

RUN apt-get update && apt-get -y install libedit-dev build-essential

RUN gem install anatomy
RUN anatomy --version
