FROM arm64v8/node:14.20.0-alpine

WORKDIR /srv
ADD . .
RUN npm install

EXPOSE 3000
CMD ["node", "server.js"]
