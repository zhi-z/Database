# redis 使用

## 1.linux下安装

```
$ wget http://download.redis.io/releases/redis-6.0.6.tar.gz
$ tar xzf redis-6.0.6.tar.gz
$ cd redis-6.0.6
$ make
```

运行：

```
# 服务端
src/redis-server
# 客户端
src/redis-cli
```



## 2.基础命令

> 1) 清除所有数据：flushall
>
> 2）启动：redis-server.exe redis.windows.conf
>
> 3）登录客户端：redis-cli.exe -h 127.0.0.1 -p 6379

