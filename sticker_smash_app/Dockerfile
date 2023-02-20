FROM node:16-alpine3.17

ARG WD="/home/StickerSmashStudy"

WORKDIR ${WD}

RUN apk update && \
    apk add bash git && \
    apk add --upgrade grep

RUN yarn global add expo-cli

RUN yarn global add expo-cli
