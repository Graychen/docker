FROM zacksleo/docker-composer:alpine
WORKDIR /var/www/html
COPY . /var/www/html
RUN apk update && \
apk add nodejs && \
#npm install cnpm -g --registry=https://r.npm.taobao.org && \
npm install puppeteer-cn && \
docker-php-ext-install sockets
#RUN apk update && apk add --no-cache curl tar fontconfig && \
#  mkdir -p /usr/share && \
#  cd /usr/share \
#  && curl -L https://github.com/Overbryd/docker-phantomjs-alpine/releases/download/2.11/phantomjs-alpine-x86_64.tar.bz2 | tar xj \
#  && ln -s /usr/share/phantomjs/phantomjs /usr/bin/phantomjs \
#  && phantomjs --version

#RUN apk update && apk add --no-cache fontconfig && \
#  mkdir -p /usr/share && \
#  cd /usr/share \
#  && curl -L https://github.com/Overbryd/docker-phantomjs-alpine/releases/download/2.11/phantomjs-alpine-x86_64.tar.bz2 | tar xj \
#  && ln -s /usr/share/phantomjs/phantomjs /usr/bin/phantomjs \
#  && phantomjs --version
#&& rm -fr $PHANTOMJS_ARCHIVE  /tmp/*
#FROM brumbrum/php-phantomjs
#FROM jerson/php-phantomjs
#npm config set registry="https://registry.npm.taobao.org" && \
#apk apk add libexif udev && \
#apk add chromium && \
#npm install -g puppeteer-core
 
#RUN apk update && apk add nodejs && npm install -g phantomjs-prebuilt
#RUN apk update && apk add --no-cache fontconfig && \
#  mkdir -p /usr/share && \
#  cd /usr/share \
#  && curl -L https://github.com/dustinblackman/phantomized/releases/download/2.1.1/dockerized-phantomjs.tar.gz | tar xz \
#  && ln -s /usr/share/phantomjs/phantomjs /usr/bin/phantomjs \
#  && phantomjs --version

#RUN set -ex \
#  && apk add --no-cache --virtual .build-deps ca-certificates openssl \
#  && wget -qO- "https://github.com/dustinblackman/phantomized/releases/download/2.1.1/dockerized-phantomjs.tar.gz" | tar xz -C / \
#  && npm install -g phantomjs-prebuilt \
#  && apk del .build-deps

#RUN apk update && apk add --no-cache fontconfig curl curl-dev && \
#    mkdir -p /usr/share && \
#    cd /usr/share \
#    && curl -L curl -Ls https://github.com/dustinblackman/phantomized/releases/download/2.1.1a/dockerized-phantomjs.tar.gz | tar xj \
#    && npm install -g phantomjs-prebuilt \
#    && phantomjs --version
#VOLUME ["/var/www/html"]
