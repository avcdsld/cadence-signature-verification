# Flow JavaScript SDK と Cadence を使った署名検証

## 要件
- Node 12
- Docker, Docker Compose

## 使い方
### インストール
```sh
yarn install
docker-compose build
```

## 動かし方

### Flow エミュレータ起動
```sh
docker-compose up
```

### 署名と署名検証
```sh
yarn start
```

### その他: Flow CLI によるキーペア生成
```sh
docker-compose exec flow-emulator flow keys generate
```

## 参考
- Flow Go SDK と Cadence を使った署名検証: https://github.com/onflow/flow-go-sdk/blob/73fe4a/examples/user_signature/main.go
