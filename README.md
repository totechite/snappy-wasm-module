Snappy WASM NPM Module
===================

実行環境
-------------------

- Docker
- CPU: x86
  - Rustのzstdライブラリがx86依存なため

開発
--------------------

イメージビルド

```bash
docker-compose build
```

Rust環境

```bash
docker-compose run build-wasm /bin/sh
```
