# Volume の解説（By Github Copilot Chat）

Docker Volume は、Docker コンテナとホストマシンの間でデータを永続化するための方法です。以下は、Docker Volume を使用するための基本的なコマンドです。

- ボリュームの作成
-

```bash
docker volume create my_volume
```

- ボリュームの一覧表示

```bash
docker volume ls
```

- ボリュームの詳細表示

```bash
docker volume inspect my_volume
```

- ボリュームの削除

```bash
docker volume rm my_volume
```

- ボリュームを使用してコンテナを起動する

```bash
docker run -v my_volume:/path/in/container my_image
```

これらのコマンドを使用することで、Docker Volume を作成し、管理し、コンテナと共有することができます。
