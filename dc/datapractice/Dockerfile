FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV PORT 80

EXPOSE 80

# VOLUME ["/app/node_modules"]

CMD ["npm", "start"]