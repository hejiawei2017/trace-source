FROM node
WORKDIR /usr/src/app
ADD . /usr/src/app
RUN npm config set registry https://registry.npm.taobao.org 
RUN npm install -g @vue/cli 
RUN npm install 
RUN npm run build

COPY --from=node /usr/src/app/dist /frontend/dist