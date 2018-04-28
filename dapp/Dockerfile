FROM mhart/alpine-node:8

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

RUN apk update && apk upgrade && \
    apk add --no-cache bash git openssh

RUN apk --update add g++ gcc libgcc libstdc++ linux-headers make python

RUN npm install -g truffle

EXPOSE 8545
EXPOSE 3000
EXPOSE 35729
# CMD [ "npm", "start" ]
