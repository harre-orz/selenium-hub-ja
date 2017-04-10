FROM selenium/node-firefox-debug:2.53.0

USER root
RUN wget https://www.ubuntulinux.jp/sources.list.d/$(cat /etc/apt/sources.list| sed -n -e 's|^deb [^ ]* \([a-z]*\) .*|\1|p'| head -1).list -O /etc/apt/sources.list.d/ubuntu-ja.list
RUN apt-get update && apt-get install -y --allow-unauthenticated ubuntu-defaults-ja && apt-get clean

USER seluser
