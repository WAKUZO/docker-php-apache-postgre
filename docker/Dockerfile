# ベースとなるDockerイメージ
FROM php:7.4-apache
# ファイルとディレクトリをコンテナにコピーします。
COPY ./web/php.ini /usr/local/etc/php/

WORKDIR /var/www/html
# PHPコンテナに入った時の作業ディレクトリ（つまりカレントディレクトリ）を指定します。
# docker-compose exec app bashというコマンドでappコンテナの中に入った場合、/var/www/htmlがカレントディレクトリになります。


# RUN apt-get update && \
#   # PDO PostgreSQL 拡張
#   apt-get install -y libpq-dev &&\
#   docker-php-ext-install pdo_pgsql

  # RUN apt-get update -qq && apt-get install -y postgre