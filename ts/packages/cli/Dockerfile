FROM node:18.19.1-alpine

RUN apk --no-cache add bash curl &&\
  curl https://cli.configu.com/install.sh | sh &&\
  rm -rf /var/cache/apk/*

ENTRYPOINT [ "configu" ]
