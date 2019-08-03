## 前言

PAI实例的「一键发布」功能提供了快速发布后台应用的能力，可以极大的提升研发效率。
本章将介绍PAI发布机制的原理，以及详细发布配置文件说明，最后提供一些官方PAI项目

## PAI发布机制

PAI实例的发布能力依赖 Git项目访问路径以及目录下面对应的 .pai.yml 文件，比如发布应用时流程如下

* 1.拉取 GitRep 目录内所有文件
* 2.执行 .pai.yml 内 start 部分的脚本内容


## 配置文件.pai.yml说明
```
deployScripts:
  start:
    - npm install
    - npm run start
  stop:
    - npm run stop
  restart:
    - npm install
    - npm run restart
```
以一个 Node.js 的PAI发布配置文件为例
* deployScripts：应用管理相关脚本目录
* start：启动应用脚本内容
* stop：停止应用脚本内容
* restart：重启应用脚本内容

## PAI官方参考配置

* Node.js：https://github.com/TencentCloudBase/pai-mate-hello-example
* Go：https://github.com/TencentCloudBase/pai-mate-hello-example-go
* Python：https://github.com/TencentCloudBase/pai-mate-hello-example-py

您可以通过参考每个官方Demo中的 .pai.yml 文件来学会如何
