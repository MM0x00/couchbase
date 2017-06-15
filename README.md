# couchbase 在线实验环境

## 软件简介

Couchbase Server是一个NoSQL文档数据库，具有用于性能，可扩展性和可用性的分布式体系结构。它使开发人员能够通过利用JSON的灵活性利用SQL的强大功能来更轻松地构建应用程序。

所属类别是数据库

特点：

利用JSON的灵活性利用SQL的强大功能来更轻松地构建应用程序。
## 软件官网

https://www.couchbase.com/

## Dockerfile 使用方法

快速启动与Couchbase服务器和Docker

以下是如何获取在Docker容器上运行的单个节点Couchbase Server集群：

步骤1：运行Couchbase Server docker容器
```
docker run -d --name db -p 8091-8094:8091-8094 -p 11210:11210 couchbase
```
步骤2：接下来，访问http://localhost:8091主机以查看Web控制台以启动Couchbase Server设置。

浏览安装向导并接受默认值。

注意：您可能需要降低分配给各种服务的RAM以适应容器资源的范围。

## 资源链接

- https://forums.couchbase.com/
- https://hub.docker.com/_/couchbase/
- https://developer.couchbase.com/documentation/server/4.5/install/getting-started-docker.html
