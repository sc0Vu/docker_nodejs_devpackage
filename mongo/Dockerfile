From alpine:3.4

MAINTAINER Peter Lai <alk03073135@gmail.com>

RUN echo 'http://dl-3.alpinelinux.org/alpine/edge/testing' >> /etc/apk/repositories && \
    apk upgrade --update && \
    apk add mongodb

# copy conf
# COPY mongo.conf /usr/local/etc/mongo/mongo.conf

EXPOSE 27017

VOLUME /data/db

CMD [ "mongod" ]