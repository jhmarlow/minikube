FROM node:12-slim
WORKDIR /app
COPY ./package.json /app/package.json
RUN npm install
COPY ./src /app/src
ENTRYPOINT ["node", "src/index.js"]