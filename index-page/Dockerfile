FROM node:18-alpine

COPY . .

RUN npm install -g serve

ENTRYPOINT serve ./web -l 8080

EXPOSE 8080