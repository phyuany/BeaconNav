# BeaconNav 优化主题

## 主题介绍

基于`BeaconNav`，原始主题仓库: <https://github.com/ZShijun/BeaconNav>

主要对样式进行优化。

## 本地二次开发

启动本地开发环境

```shell
# 启动服务
docker compose up -d
# 进入容器里
docker exec -it typecho-server bash
```

进入容器里，执行以下命令挂载主题

```shell
ln -s /data/ /app/usr/themes/BeaconNav
```
