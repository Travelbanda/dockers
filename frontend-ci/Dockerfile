FROM node:8.11.3-alpine

RUN apk update && apk upgrade
RUN apk add --no-cache bash git openssh
RUN apk add --no-cache udev ttf-freefont chromium

ENV CHROME_BIN=/usr/bin/chromium-browser
