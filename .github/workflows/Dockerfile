FROM node:14

WORKDIR /gha-lab

COPY package*.json ./
RUN npm install --production

COPY . .

EXPOSE 3000
CMD ["node", "index.js"]
