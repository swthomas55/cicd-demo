FROM node:10.1.0-alpine
EXPOSE 3000
ENV GREETING='Hello Worlds!'
WORKDIR /app

COPY package.json .
RUN npm install

COPY *.js ./

USER node
CMD ["node", "app.js"]