FROM node:14-alpine

ENV NODE_ENV=production

WORKDIR /app/frontend/

ENV PATH /app/node_modules/.bin:$PATH

COPY package*.json /app/frontend/
RUN npm install

COPY . /app/frontend/

EXPOSE 3000

CMD ["npm", "start"]