FROM node:16.15.0
WORKDIR /app
COPY ./package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]

#docker build -t conversao-temperatura .
#docker container run -d -p 8080:8080 conversao-temperatura
