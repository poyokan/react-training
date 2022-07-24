FROM node:16.15-alpine
# WORKDIR /usr/src/app



WORKDIR /react-training/

COPY package*.json /react-training/

RUN npm install

COPY ./ /react-training/

EXPOSE 3000

CMD ["npm", "start"]
