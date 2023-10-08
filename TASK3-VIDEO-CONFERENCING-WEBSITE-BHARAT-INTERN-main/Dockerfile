FROM node:latest
WORKDIR app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3030
CMD ["node", "script.js"]
