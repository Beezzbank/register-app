FROM node:18.12.1-alpine

WORKDIR /register-app/

COPY . /register-app/

RUN npm install

RUN cd Docker

EXPOSE 3000

CMD ["npm","start"]