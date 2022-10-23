# k8s-go-prologue

k8s minikubeで構築した go 環境

## 初回

```bash
# ビルド
docker-compose build

# ネットワーク作成
docker network create prologue-network

# 起動
docker-compose up
```

## 2回目以降

```bash
docker-compose up
```
