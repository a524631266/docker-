# 查找镜像
- 1. 通过[docker hub官网](https://registry.hub.docker.com),搜索包
- 2. 命令行
 ```
  $ docker search [options] TERM

    --
 ```


# 拉取镜像
```
 $ docker pull ubuntu:16.04
```
加速
使用--registry-mirror选项
1.修改 /etc/default/docker
2.添加 DOCKER_OPTS = "--registry-mirror=http://mirror-add"

可以通过DAOCLOUD提供的url

# 推送镜像

```
 $ docker push name:id

```