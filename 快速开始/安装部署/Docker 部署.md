# Docker 部署

官方提供 [firekylin/firekylin](https://hub.docker.com/firekylin/firekylin) Docker 镜像。下面是以 SQLite 存储方式为例的一个快速启动程序的命令实例。

```sh
docker run -d \
  --name firekylin \
  --restart unless-stopped \
  -p 8360:8360 \
  -v firekylin-data:/var/lib/firekylin \
  firekylin/firekylin:latest
```

启动后访问 `http://127.0.0.1:8360` 完成网页安装。在数据库配置中：

- 数据库选择 `SQLite`。
- 数据库名可保持默认的 `firekylin`。
- 数据库文件目录填写 `/var/lib/firekylin`。

Docker 会自动创建名为 `firekylin-data` 的持久卷。SQLite 数据库、Firekylin 数据库配置和上传文件都会保存在该卷中，重建容器时应继续挂载同一个卷。

升级前请备份 `firekylin-data` 卷。自定义主题、插件以及其他站点文件需要另行持久化和备份。确认新容器可访问文章、后台和图片后，再删除旧容器。
