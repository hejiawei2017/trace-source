FROM node as builder
WORKDIR /usr/src/app
ADD . /usr/src/app
RUN npm config set registry https://registry.npm.taobao.org 
RUN npm install -g @vue/cli 
RUN npm install 
RUN npm run build
CMD['docker cp builder:/usr/src/app/dist /frontend/dist']