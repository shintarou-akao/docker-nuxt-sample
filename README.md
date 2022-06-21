## 概要
Nuxt.jsのDocker開発環境サンプル

## 開発環境構築手順
```
$ git clone git@github.com:shintarou-akao/docker-nuxt-sample.git
$ docker compose up -d --build
$ docker compose exec app sh
# npx nuxi init .
# yarn install
# yarn dev -o
```