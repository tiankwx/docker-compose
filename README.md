# docker-compose
docker-compose 例子

# 使用方法
```
# docker-compose up -d
# /usr/local/bin/docker-compose -f /home/phablet/Desktop/docker-douban-curl/docker-compose.yml up -d
# 启动，-d 后台运行
# docker-compose stop 
# docker-compose stop 命令将停止运行的容器，但不会删除它们。

# docker-compose down -v
# docker-compose down命令将停止运行的容器，并且会删除已停止的容器以及已创建的所有网络。 
# 我们可以down进一步迈出第一步，并添加-v标记以删除所有卷。这对于通过运行在环境中进行完全重置非常有用docker-compose down -v。
```
