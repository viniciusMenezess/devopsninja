# FROM node:alpine
FROM node:alpine

RUN mkdir -p /src 

# Definir diretório de trabalho
WORKDIR /src
ADD . /src

# Expor porta 80
EXPOSE  8080

# Rodar o app usando nodemon
CMD ["node", "/src/index.js"]