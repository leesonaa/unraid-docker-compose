# unraid-docker-compose
- 1.运行命令
```bash
docker compose /path/compose.yml up -d
```
- 2.插件运行 Compose Manager直接编辑再compose up

- 重建图标缓存
```bash
rm -rf /var/lib/docker/unraid/images/* && rm -rf /var/local/emhttp/plugins/dynamix.docker.manager/images/* 
```