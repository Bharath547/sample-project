FROM node

WORKDIR /node-api
COPY package.json .
COPY app.js .
RUN npm install
EXPOSE 3000

CMD ["npm", "start"]
