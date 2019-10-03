# Study Docker

## Docker Command

### コンテナ起動

```
$ docker-compose up -d
```

ファイルを指定して起動する

```
$ docker-compose -f docker-compose.python.yml up -d
```

### ログを見る

```
$ docker-compose logs
```

### コンテナに接続する

```
$ docker-compose exec `service name` sh
```

### コンテナに date コマンドを発行する

```
$ docker-compose exec `service name` date
```

### コンテナの停止

```
$ docker-compose stop
```

### コンテナの削除

```
$ docker-compose down
```
