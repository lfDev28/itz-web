# Vite app dockerfile
FROM node:14.17.0-alpine3.13 as build-stage

WORKDIR /app

COPY package.json package-lock.json ./
RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "run", "dev"]

