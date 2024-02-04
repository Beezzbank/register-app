FROM node:18.12.1-alpine

WORKDIR /register-app/

COPY . /register-app/


RUN apk update \ 
&& apk install -y curl \
&& npm install


EXPOSE 3000

CMD ["npm","start"]