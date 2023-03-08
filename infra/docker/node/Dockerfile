FROM node:18

# node.js の環境変数を定義する
# 本番環境では production
ENV NODE_ENV=development

# 雛形を生成するのに必要なパッケージのインストール
RUN npm install -g pm2

# ディレクトリを移動する
WORKDIR /app

# ポート3000番を開放する
EXPOSE 3000