---
tag:
  - docker
---

# 容器化和虚拟化

![](https://coding-net-production-pp-ci.codehub.cn/67643644-9aca-4484-9cab-edfd57209b81.png)

> 原文地址：https://medium.com/edureka/devops-interview-questions-e91a4e6ecbf3
> 原文作者：Saurabh Kulshrestha

让我们看看你对容器和虚拟机的了解程度。

* 容器提供实时资源调配和可拓展性，虚拟机提供的资源调配速度较慢
* 与虚拟机相比，容器是轻量级的
* 与容器相比，虚拟机的性能有限
* 与虚拟机相比，容器具有更好的资源利用率

<!-- more -->

## Q1. 什么是容器？

容器提供了从开发人员的笔记本电脑到测试环境、从类生产环境到生产环境一致的运行环境。

接下来给出容器的定义，容器由一个完整的运行环境组成：将一个应用程序，以及它所有的依赖项、库和其他二进制文件，以及运行它所需的配置文件打包到一起。将应用平台及其依赖项容器化，可以消除操作系统版本和底层基础架构间的差异。


![](https://coding-net-production-pp-ci.codehub.cn/b64292f5-9f98-4945-bc25-b62b0e6ecaa6.png)

## Q2. 容器化相比虚拟化有哪些优势？

以下是容器化相对于虚拟化的优势：
* 容器提供实时资源调配和可拓展性，虚拟机提供的资源调配速度较慢
* 与虚拟机相比，容器是轻量级的
* 与容器相比，虚拟机的性能有限
* 与虚拟机相比，容器具有更好的资源利用率

## Q3. 容器（在我们的例子中指 Docker）与管理程序虚拟化（vSphere）有何不同？有哪些好处？

以下是一些不同之处。请确保在你的回答中包含这些差异：

![](https://coding-net-production-pp-ci.codehub.cn/67643644-9aca-4484-9cab-edfd57209b81.png)

- Q4. 什么是 Docker 镜像？

Docker 镜像是 Docker 容器的来源，换句话说，Docker 镜像用于创建容器。使用 build 命令创建镜像，当开始运行时，它们将生成一个容器。镜像存储在 Docker 注册表中，如 registry.hub.docker.com，因为它们可能变得非常大，镜像被设计成由其他镜像层组成，允许在通过网络传输镜像时发送最小的数据量。

提示：请关注 Dockerhub，以便回答有关预可用镜像的问题。
