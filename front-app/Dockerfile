#Primera Etapa
FROM node:18.13.0

WORKDIR /app

COPY package*.json /app/

RUN npm install

COPY . /app/

EXPOSE 4200

CMD ["npm", "run", "start"]

