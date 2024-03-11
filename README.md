# MondoDB学習用リポジトリ

- 参考URL：https://qiita.com/saba1024/items/f2ad56f2a3ba7aaf8521

# MongoDB環境構築

- 参考URL：https://zenn.dev/optimisuke/articles/d6b248d45f4f5c

# MongoDBユーザー認証手順

- 参考URL：https://qiita.com/h6591/items/68a1ec445391be451d0d

# MongoDBコマンド集

- 参考URL：https://qiita.com/yuji0602/items/c55e2cb75376fd565b4e

# MongoDB Shellの使い方

- 参考URL：https://qiita.com/ekzemplaro/items/dd712c2af1c908a97965

# MongoDBログイン

- MongoDBのコンテナ(Docker)を起動する。
  ```
  docker-compose up -d
  ```

- MongoDBのコンテナに入る。
  ```
  docker exec -it mongo bash
  ```

- mongoコンテナ内で、以下のコマンドを実行し、mongoDBにログインする
  ```
  mongosh -u root -p password
  ```

- DBを変更する
  ```
  use admin
  ```
