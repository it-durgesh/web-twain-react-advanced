FROM node:22-alpine
WORKDIR /usr/src/app

COPY package.json package-lock.json* ./
RUN npm install

COPY . .
EXPOSE 2020
CMD ["npm", "start"]
