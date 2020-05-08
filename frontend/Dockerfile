FROM node
WORKDIR /usr/src/app
ADD . /usr/src/app
RUN npm config set registry https://registry.npm.taobao.org/ && \  
    npm install -g @vue/cli && \
    npm i && \
    npm run build

