FROM node:22

ADD package.json package-lock.json ./
RUN npm ci

ADD . .

CMD [ "npm", "start" ]