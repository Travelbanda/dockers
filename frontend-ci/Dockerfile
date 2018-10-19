FROM node:10.12.0-alpine

RUN apk update
RUN apk add --no-cache bash git openssh
RUN apk add --no-cache udev ttf-freefont chromium

ENV CHROME_BIN=/usr/bin/chromium-browser
