# docker-YApi

在 [Docker](https://www.docker.com/) 中运行 [YApi](https://github.com/YMFE/yapi)。



<!-- TOC depthFrom:2 -->

- [要求](#要求)
- [安装](#安装)
- [如何配置](#如何配置)
- [如何重启](#如何重启)
- [如何迁移](#如何迁移)
- [YApi 相关资源推荐](#yapi-相关资源推荐)
- [许可](#许可)

<!-- /TOC -->

## 要求

require :docker docker-compose 

## 安装
```
git clone git.path

cd dir

docker-composer up -d
```

## 如何配置

### 通过环境变量配置（推荐）

`cp env.example .env`
修改个人配置

## 如何重启

若你修改了配置，务必重启应用才能生效：

```bash
docker-compose restart 
```


## 如何迁移

docker image 镜像打包

## YApi 相关资源推荐

- [YApi-X](https://github.com/fjc0k/YApi-X#readme)

  YApi 二次开发版，进行了很多功能上的增强，原生支持 Docker 安装。

- [YApi-X 浏览器插件](https://github.com/fjc0k/YApi-X/tree/master/chrome-extension#readme)

  为 YApi-X 开发的浏览器跨域与文件上传插件，同时支持 YApi 官方版。

- [YApi to TypeScript](https://github.com/fjc0k/yapi-to-typescript#readme)

  根据 YApi 的接口定义生成 TypeScript 的接口类型及其请求函数代码，同时支持生成 React Hooks 代码。

## 许可

Jero © MIT
