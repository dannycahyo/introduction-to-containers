FROM node:12-alpine

USER node

RUN mkdir /home/node/src

WORKDIR /home/node/src

COPY --chown=node:node package-lock.json package.json ./

RUN npm i

COPY --chown=node:node . .


CMD [ "node", "index.js" ]
