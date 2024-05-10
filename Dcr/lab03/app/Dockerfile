FROM node:18-alpine

WORKDIR /app
COPY . .

RUN yarn install --production

EXPOSE 3000

ENTRYPOINT [ "node" ]
CMD [ "src/index.js"]