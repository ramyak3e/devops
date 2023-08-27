FROM node:14
WORKDIR /home/ubuntu/devops/shoestop
COPY package.json .
RUN npm install --quiet
COPY . .
CMD ["node" , "server.js"]
