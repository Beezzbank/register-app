FROM node:18.12.1-alpine

WORKDIR /register-app/

COPY . /register-app/


RUN apt update && apt install -y curl

RUN npm install


EXPOSE 3000

CMD ["npm","start"]