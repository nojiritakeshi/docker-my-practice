# 【 ３部: イメージのビルド 】

## ファイルツリー

```
$ tree .

.
|-- docker
|   |-- app
|   |   |-- Dockerfile        ← New
|   |   |-- mail.ini          ← New
|   |   `-- mailrc            ← New
|   `-- db
|       |-- Dockerfile        ← New
|       `-- my.cnf            ← New
`
```

## App イメージのビルド

```
$ docker image build             \
    --tag docker-practice:app    \
    --file docker/app/Dockerfile \
    .
```

## DB イメージのビルド

```
$ docker image build            \
    --tag docker-practice:db    \
    --file docker/db/Dockerfile \
    .
```
