# Taskmgr

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.5.0.

## 几个常用的命令

    npm -i --save packageName  // 软件依赖

    npm -i --save-dev packageName  // 开发依赖

    ng new projectName  // 新建Angular项目

    ng build -prod  // 生产环境编译

    ng serve  // 启动开发服务器

## Mock Rest API

json-server: 用于快速搭建 REST API 的利器

    npm install -g json-server

## taskmgr

    ng new taskmgr -si --style=scss

    cd taskmgr

    npm install

    ng g m core  // 创建核心模块（在系统中只加载一次）

    ng g m shared  // 创建共享模块

    ng g c core/header --spec=false

    npm install --save @angular/material@2.0.0-beta.7
