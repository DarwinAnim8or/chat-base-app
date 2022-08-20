FROM node:latest

#move everything into place
WORKDIR /home/node/app

COPY *.js /home/node/app/
COPY package.json /home/node/app/

#prep
RUN npm install
EXPOSE 3000
