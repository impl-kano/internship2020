FROM node:12 as web-build

WORKDIR /app

# package.jsonをイメージにコピー
COPY package.json /app

RUN npm install

# サーバーを起動
CMD ["npm", "start"]