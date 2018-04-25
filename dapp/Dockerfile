FROM mhart/alpine-node:8

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

RUN apk update && apk upgrade && \
    apk add --no-cache bash git openssh

run apk --update add g++ gcc libgcc libstdc++ linux-headers make python

EXPOSE 8545
# CMD [ "npm", "start" ]
