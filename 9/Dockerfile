FROM node:9-alpine

RUN apk add --no-cache tini

WORKDIR /app
RUN chown -R node /app

USER node

ENTRYPOINT ["/sbin/tini", "--"]
