FROM grababyte/alpine-base:0.7.5

LABEL devops.grababyte.image.authors="GrabAByte"

ENV JAVA_HOME="/usr/lib/jvm/java-11-openjdk"
ENV PATH="$PATH:${JAVA_HOME}/bin"

RUN \
  apk add --no-cache openjdk11==11.0.14_p9-r0 && \
  rm -rf /var/cache/apk/*
