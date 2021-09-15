FROM node:14.14.0-alpine
Workdir '/app'
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]