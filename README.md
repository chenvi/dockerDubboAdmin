# 下载源码：
```
git clone https://github.com/chenvi/dockerDubboAdmin.git
```

# 构建脚本
```
docker build -t dockerdubbo .
```

# 运行容器
```
docker run -d --name dockerdubbo -p 8080:8080 --link zookeeper:zookeeper dockerdubbo
```

