# Minecraft Servers

本项目可以用于直接启动Minecraft服务端

## 推荐环境

Docker: [jokin1999/mc-base](https://hub.docker.com/repository/docker/jokin1999/mc-base)

## 使用方法

- 克隆或下载本项目中指定服务端版本的`branch`
- 挂载项目文件夹至Docker环境（记得打开服务端口，默认25565）
- 运行`java -jar [服务端jar包]`即可
