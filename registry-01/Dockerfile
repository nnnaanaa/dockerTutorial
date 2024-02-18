# イメージの取得
FROM ubuntu:latest

# Nginx用レポジトリファイルのコピー
ADD nginx.repo /etc/apt/sources.list.d/

# Nginxのインストール
RUN apt-get update && apt-get install -y nginx