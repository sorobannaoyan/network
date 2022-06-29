# ネットワークを練習するやつ
OS ubuntu 18.04

## ubuntuコンテナを立ち上げる
```sh
docker-compose up ubuntu
```

## 立ち上げたubuntuのコンテナにsshで接続
windows用のsshクライアントを入れておくと良いです
```sh
ssh -p 2222 root@127.0.0.1
```
パスワードは"asd123"

## Lan内からの接続もできる？
例: ubuntuのコンテナが立っているPCのIPアドレス
192.168.1.10
```sh
ssh -p 2222 root@192.168.1.10
```
