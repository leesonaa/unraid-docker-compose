# unraid-docker-compose
```bash
docker compose /path/compose.yml up -d
```
- 重建图标缓存
```bash
rm -rf /var/lib/docker/unraid/images/* && rm -rf /var/local/emhttp/plugins/dynamix.docker.manager/images/* 
```