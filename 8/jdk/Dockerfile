FROM openjdk:8-jdk-alpine
RUN  echo "http://mirrors.aliyun.com/alpine/v3.9/main" > /etc/apk/repositories \
    && echo "http://mirrors.aliyun.com/alpine/v3.9/community" >> /etc/apk/repositories \
    && apk --update add --no-cache freetype ttf-dejavu \
    && rm -rf /var/cache/apk/*
