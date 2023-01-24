FROM node:18.11.0
WORKDIR /app
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]


#Criar imagem do Docker para rodar a aplicação em um container.
