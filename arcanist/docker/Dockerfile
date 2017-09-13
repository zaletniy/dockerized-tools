FROM ubuntu
MAINTAINER Illia Svyrydov

RUN apt-get update
RUN apt-get -y install git php php-curl vim
RUN mkdir /usr/lib/arc
RUN git clone https://github.com/phacility/libphutil.git /usr/lib/arc/libphutil
RUN git clone https://github.com/phacility/arcanist.git  /usr/lib/arc/arcanist
RUN touch /root/.arcrc

ENV PATH "$PATH:/usr/lib/arc/arcanist/bin"
ENV EDITOR "vim"

WORKDIR /code
