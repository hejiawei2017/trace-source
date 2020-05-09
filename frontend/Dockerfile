FROM node:10-alpine
WORKDIR /usr/src/app
ADD . /usr/src/app
RUN npm config set registry https://registry.npm.taobao.org/
RUN npm install -g @vue/cli
RUN npm i 
RUN npm run build
