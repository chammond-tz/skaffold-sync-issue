FROM node:lts-alpine

ARG NODE_ENV=production

WORKDIR /var/www

COPY package*.json .
RUN npm i

COPY . .

CMD ["npm", "start"]