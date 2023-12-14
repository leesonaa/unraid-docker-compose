# unraid-docker-compose
***✔.env为compose.yml默认的环境变量文件，必要***
***✔app.env为moviepilot的环境变量引用文件，用的到就留着，用不到就不留，非必要***
- 1.运行命令
  - 下载这个库的几个文件到你的设备上，用户家目录或者root家目录都可以
```bash
docker compose /path/compose.yml up -d
```
- 2.插件运行 Compose Manager直接编辑再compose up

- 重建图标缓存
```bash
rm -rf /var/lib/docker/unraid/images/* && rm -rf /var/local/emhttp/plugins/dynamix.docker.manager/images/* 
```
