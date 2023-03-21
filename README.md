## 開発環境構築

```shell
$ cd docker

# dockerコンテナを作成します.
$ docker compose up -d

# http://localhost:8888/にアクセスします.

# dockerコンテナを削除します.
$ docker compose down --rmi all --volumes --remove-orphans
```
