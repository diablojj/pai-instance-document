## 前言
* Demo名称：小程序商城
* Demo效果：使用PAI实例 5 分钟搭建一个小程序商城
* Demo包含：Node.js 10.16、Sqlite 3.7、NideShop（开发者 tumobi）
* Demo代码：[NideShop服务端](https://github.com/TencentCloudBase/pai-template-nideshop)、[NideShop小程序端](https://github.com/tumobi/nideshop-mini-program)
* PAI实例默认环境包含：CentOS 7.0、Nginx 1.12、域名、Let’s Encrypt SSL证书、Git、PAI Agent

## 1.登录PAI管理页面
PAI实例购买、查看、访问管理页面请查看 [PAI实例使用指南>>>](https://github.com/diablojj/pai-instance-document/blob/master/使用指南.md)

<p align='center'>
<img src='https://pai0803-1252462967.cos.ap-chengdu.myqcloud.com/1.png' title='images' style='max-width:1200px'></img>
</p>

打开 PAI 实例管理页面，账号、密码为该云服务器的 SSH 登录账号和密码（若忘记密码请前往腾讯云云服务器控制台修改）

## 2.使用PAI部署服务端
### 2-1.在PAI管理页发布Demo「官方实例-小程序商城」


### 2-2.检查成功



## 3.配置小程序端
### 3-1.下载小程序端源码

### 3-2.导入项目到微信


### 3-3.修改config内服务器域名


### 3-4.修改小程序信任的服务器域名
小程序端会校验其访问域名是否为您在微信开放平台内填写的信任域名（[详细信息见>>>](https://developers.weixin.qq.com/miniprogram/dev/framework/ability/network.html
)），有两个方法可以通过校验，

#### I.前往「微信开放平台-开发-开发设置-服务器域名」填写PAI实例域名



#### II.在微信IDE内关闭校验


## 4.体验Demo效果


编译小程序端后，左侧预览界面展示 NideShop 小程序商城的首页，您已成功搭建一个小程序商城

想创建一个您自己的小程序商城？请复制 Demo 到您的 Git 账号内，修改任意内容
