#FROM node:latest

#RUN mkdir -p /usr/src/app

#COPY package*.json /usr/src/app/

#WORKDIR /usr/src/app

#RUN npm install

#COPY . /usr/src/app

#CMD ["npm","start"]

#EXPOSE 8000


FROM node:slim

#ENV NODE_OPTIONS=--openssl-legacy-provider
ENV NODE_OPTIONS="--openssl-legacy-provider --max_old_space_size=4096"

WORKDIR /src
COPY . .
RUN yarn install
EXPOSE 8000

CMD [ "yarn", "start" ]