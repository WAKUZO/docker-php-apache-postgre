# ベースとなるDockerイメージ
FROM php:7.4-apache
# ファイルとディレクトリをコンテナにコピーします。
COPY ./web/php.ini /usr/local/etc/php/

# RUN apt-get update && \
#   # PDO PostgreSQL 拡張
#   apt-get install -y libpq-dev &&\
#   docker-php-ext-install pdo_pgsql

  # RUN apt-get update -qq && apt-get install -y postgresql