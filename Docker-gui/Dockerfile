FROM ubuntu:14.04

RUN apt-get update
RUN apt-get install -y firefox

RUN useradd -d /home/user -s /bin/bash -m user -u 501 -g 20

USER user
ENV HOME /home/user
CMD /usr/bin/firefox
