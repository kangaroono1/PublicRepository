# 一、SpringCloudToy - 后端项目

## 1.模块介绍

- feign-api : 远程调用

- gateway ：网关 

  - 若需要监考网关，则需运行相应jar包
  - 1. cmd> cd ./NeedUnit/sentinel-dashboard-1.8.6.jar
    2. cmd> java -jar sentinel-dashboard-1.8.6.jar

- item-service

- news-service

- user-service

## 2.必须提前启动注册中心Nacos！

- 启动方法：
  1. 解压 ./NeedUnit/ 路径下的 nacos-server-1.4.5.zip
  2. cmd> cd ./NeedUnit/nacos/bin
  3. cmd> startup.cmd -m standalone
  4. 进入所显示的路径http://192.168.17.1:8848/nacos/index.html
  5. 输入[ 账户=nacos, 密码=nacos]
  6. 各注册模块上线后，可在"主页 -> 服务管理 -> 服务列表"中查看

# 二、NeedUnit - 所需插件与数据库文件

## 1.MySQL数据库文件

- ./NeedUnit/sql-file/
  - cloud_db_item.sql
  - cloud_db_news.sql
  - cloud_db_user.sql

## 2.网关 Gateway：

- sentinel-dashboard-1.8.6.jar

## 3.注册中心&配置中心 Nacos：

- nacos-server-1.4.5.zip

## 4.lombok插件

- lombok-plugin-0.33-2020.1