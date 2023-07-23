# syntax=docker/dockerfile:1

FROM node:20-alpine
WORKDIR /1-node-farm/starter
COPY . .
RUN yarn install --production
CMD ["node", "index.js"]
EXPOSE 8000
