# 标题为unraid-docker-compose 实际任意docker环境下都可以用
### 食用说明
***✔.env为compose.yml默认的环境变量文件，必要*** \
***✔app.env为moviepilot的环境变量引用文件，用的到就留着，用不到就不留，非必要***
- 1.运行命令
  - 下载这个库的几个文件到你的设备上，用户家目录或者root家目录都可以
```bash
docker compose /path/compose.yml up -d
```
- 2.插件运行 Compose Manager直接编辑再compose up

  - unraid重建图标缓存命令，其他系统无视即可
```bash
rm -rf /var/lib/docker/unraid/images/* && rm -rf /var/local/emhttp/plugins/dynamix.docker.manager/images/* 
```
- 3.关于 .env 里媒体文件的说明如下图
![2023-12-14-1832](https://github.com/leesonaa/unraid-docker-compose/assets/97571961/e7390d58-8ae9-40ea-8562-f1bb2eb01f8d)
