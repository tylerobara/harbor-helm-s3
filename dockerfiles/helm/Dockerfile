FROM alpine

RUN apk update && apk add bash

RUN wget https://get.helm.sh/helm-v3.15.2-linux-amd64.tar.gz \
    && tar xvf helm-v3.15.2-linux-amd64.tar.gz \
    && mv linux-amd64/helm /usr/local/bin/helm \
    && rm -rf linux-amd64 helm-v3.15.2-linux-amd64.tar.gz \
    && rm -rf /var/cache/apk/*