FROM node

WORKDIR /app

RUN npm install -g @vue/cli
RUN npm i -g @vue/cli-init

COPY ./start.sh ./start.sh

RUN chmod +w ./start.sh

RUN ./start.sh