<p align="center"><a href="https://oddfar.com/" target="_blank" rel="noopener noreferrer"><img width="180" src="https://note.oddfar.com/img/web.png" alt="logo"></a></p>

<p align="center">
  <a href="https://github.com/oddfar/campus-imaotai/stargazers"><img src="https://img.shields.io/github/stars/oddfar/campus-imaotai.svg"></a>
	<a href="https://github.com/oddfar/campus-imaotai/blob/master/LICENSE"><img src="https://img.shields.io/github/license/oddfar/campus-imaotai.svg"></a>
</p>



<p align="center"> i茅台app自动预约，每日自动预约，支持docker一键部署</p>

部署：
将jar包拷贝到jar目录

查看镜像：docker images

docker rm -f campus-server campus-nginx  && docker rmi campus-imt-v108-campus-server && docker-compose up -d

## 项目介绍

i茅台app，每日自动预约茅台

- [x] 平台注册账号(可用i茅台)
- [x] 添加多个用户
- [x] 自动预约
- [x] 类型选择（本市出货量最大的门店，或位置附近门店）
- [x] 自动旅行
- [x] 首次旅行分享
- [x] 获取申购耐力值
- [x] 自定义时间/随机时间预约或旅行
- [x] 结果消息推送

此项目使用 **Campus** 进行编写：<https://github.com/oddfar/campus>

## 使用教程

- 文档

  <https://github.com/oddfar/campus-imaotai/wiki>

有问题请查看文档，查找 [issues](https://github.com/oddfar/campus-imaotai/issues) 上是否有相同问题！

若没有则提交 [issues](https://github.com/oddfar/campus-imaotai/issues)  ，附带详细的错误原因

不会Docker部署的，可使用客户端：<https://github.com/lisongkun/hygge-imaotai>

