FROM node:16-alpine

ENV REACT_APP_GO_ENDPOINT=${REACT_APP_GO_ENDPOINT}

WORKDIR /app

COPY package.json ./

RUN npm install

COPY . .

CMD ["npm", "start"]