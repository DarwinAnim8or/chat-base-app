FROM node:latest

#move everything into place
WORKDIR /home/node/app

COPY *.js /home/node/app/
COPY package.json /home/node/app/

#prep
ENV NODE_ENV=production
RUN npm install
CMD ["node", "index.js"]
EXPOSE 3000
