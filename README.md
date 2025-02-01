# postgresql-on-docker

## 接続方法

```bash
# ローカルPC上で実行
docker-compose up -d
docker exec -ti postgres /bin/bash

# コンテナ内で実行
psql -U postgres-user -d postgres-db -h localhost
```
