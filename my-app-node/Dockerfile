FROM node:latest

COPY . /home/app

WORKDIR /home/app/

RUN npm install

EXPOSE 3001

CMD ["node", "api"]