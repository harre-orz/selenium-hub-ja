FROM selenium/node-firefox:2.53.0

USER root
RUN apt-get update && apt-get install -y fonts-ipaexfont-gothic fonts-ipaexfont-mincho language-pack-ja \
 && rm -rf /var/lib/apt/lists/* /var/cache/apt/*

USER seluser
