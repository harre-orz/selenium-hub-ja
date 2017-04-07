FROM selenium/node-firefox

USER root
RUN wget https://www.ubuntulinux.jp/sources.list.d/xenial.list -O /etc/apt/sources.list.d/ubuntu-ja.list
RUN apt-get update && apt-get install -y --allow-unauthenticated ubuntu-defaults-ja && apt-get clean

USER seluser
