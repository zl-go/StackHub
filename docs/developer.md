# Developer Guide

## 架构

### 微服务

存在的微服务以及选型：  

* System
* MQ
* Monitor: NetData
* SSH Ternimal
* File Browser
* Storage
* User
* API gateway: Kong
* Web-Container
* Web-DB
* Proxy&DNS（待定）
* App&CLI（开发）

![image](https://user-images.githubusercontent.com/16741975/216497356-3913abd2-0b75-4619-8c40-512079e35f5b.png)


### 基础组件

技术选型如下：

* 架构：JS UI + API Backend  
* 后端：Python, Docker, Docker-compose, FastAPI, Typer  
* API生成与测试：apipost/apifox
* 身份验证：supertokens

### 产品文件目录

便于升级、便于用户使用的产品文件目录组织结构

### Contributor

* 类型标签：Bug, enhancement, Documetation
* 过程标签：PRD, Dev, QA(include deployment), Documetation
