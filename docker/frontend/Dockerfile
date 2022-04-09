FROM node:16.5.0

ENV LANG C.UTF-8
RUN set -x && apt upgrade && apt update && apt install -y build-essential
RUN yarn global add swagger-cli && yarn global add ibm-openapi-validator@0.57.4
