FROM node:18.12.1-alpine

WORKDIR /register-app/

COPY . /register-app/

RUN npm install
RUN apt install curl

EXPOSE 3000

CMD ["npm","start"]