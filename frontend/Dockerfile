FROM node:18.18.0

WORKDIR /app

RUN npm install -g npm@8.5.1 && npm install create-next-app

USER node

#実行用コマンド
#sudo docker compose run --rm frontend npx create-next-app@12.3 tmp  && mv tmp/* . && mv tmp/.* . && rm -r tmp