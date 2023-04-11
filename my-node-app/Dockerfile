FROM node:12-stretch

USER node

WORKDIR /home/node/src

COPY --chown=node:node index.js /home/node/index.js

CMD ["node", "index.js"]