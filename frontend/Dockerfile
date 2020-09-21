FROM node:12.18.0-alpine

RUN mkdir /frontend
WORKDIR /frontend
COPY ["package.json", "yarn.lock", "./"]
RUN yarn install