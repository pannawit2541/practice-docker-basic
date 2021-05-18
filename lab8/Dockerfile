FROM node:14-alpine3.12
WORKDIR /home/node
COPY package*.json ./
RUN yarn
COPY . ./
CMD [ "yarn", "start" ]
EXPOSE 80