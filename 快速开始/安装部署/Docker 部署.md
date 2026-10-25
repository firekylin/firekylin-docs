# Docker 部署

仓库提供 Dockerfile，可从需要部署的版本自行构建，避免将主分支功能与已发布镜像混淆。

```sh
git clone https://github.com/firekylin/firekylin.git
cd firekylin
docker build -t firekylin-local .
docker volume create firekylin-data
docker run -d --name firekylin -p 8360:8360 -v firekylin-data:/var/lib/firekylin firekylin-local
```

访问 `http://127.0.0.1:8360` 完成网页安装。该镜像使用核心源码布局，入口脚本把持久卷中的 `db.js` 和 `upload` 链接到程序目录。数据库服务需要使用容器可访问的地址，不能将另一个容器的数据库地址填写为 localhost。

升级前备份数据库和持久卷。自定义主题、插件以及其他站点文件也应单独持久化和备份；上述卷仅覆盖入口脚本声明的配置和上传目录。确认新容器可访问文章、后台和图片后再删除旧容器。
