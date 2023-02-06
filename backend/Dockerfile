FROM node:14

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

ENV MONGODB_USERNAME=root
ENV MONGODB_PASSWORD=secret
ENV MONGODB_DB=test

EXPOSE 80

CMD ["npm","start"]