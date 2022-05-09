FROM node

WORKDIR /home/node/app

COPY *.js ./
COPY package.json ./

RUN ["npm", "install"]

ENV NODE_ENV=production

CMD ["node", "index.js"]

EXPOSE 3000