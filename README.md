# tommax-infra

部署与本地环境。`compose/` 提供本地一键开发环境：PostgreSQL 16 / Redis 7 / MinIO（+可选 asynqmon，`--profile tools`）。

```bash
docker compose -f compose/docker-compose.yaml up -d
```
K8s Helm/ArgoCD 配置在 Phase 1 后补充。
