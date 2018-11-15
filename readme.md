## LaraCMS 后台管理系统 

如果你觉得还不错，请 Star , Fork 给作者鼓励一下。

## QQ群：
**LaraCMS官方①群**: 172960867


## 说明

## LaraCMS 功能模块：
- 用户管理
- 权限管理
- 角色管理
- 站点信息
- 友情链接
- 栏目导航
- 分类管理
- 文章管理
- 页面管理
- 幻灯管理
- 微信公众号管理
- 第三方登录
- 前端 API
- 文章多图，多附件管理
- 集成文件秒传，分片上传
- 自定义表单
- 分词搜索
- 万能表单

## LaraCMS 特性：
- 支持文章多图
- 支持文章多附件
- 支持文件秒传，分片上传...等功能

预览：https://www.56br.com/

基于 laravel 5.5 开发，包含了 内容管理 和 API 服务两部分。

LaraCMS 最初试图用 Laravel 为自己打造一把锋利建站工具，如今已渐渐成熟可用了，还是继续开源出来，提供给有需要的朋友使用，也希望自己能够继续完善。

目前基本上能满足各种企业站的需求了，下一步计划将商城模块集成进来。可能需要很长一段时间才能更新了，而且下一版本可能会改用扩展的方式开发，便于以后的升级维护。

如果想要商用需自行测试评估可用性。

之前因为功能变化频繁，未写使用说明文档，后面我会抽时间补上。

### 使用对象
有一定基础的 Laravel 开发者，非普通站长。

### 预览

<p><img src="http://img.56br.com/images/laracms-login.png"></p>
<p><img src="http://img.56br.com/images/laracms-main.png"></p>
<p><img src="http://img.56br.com/images/laracms.jpg"></p>

- http://img.56br.com/images/laracms-login.jpg
- http://img.56br.com/images/laracms-main.jpg
- http://img.56br.com/images/laracms.jpg


## 环境需求

- PHP 7.1+
- Mysql 5.7+

## 安装

```shell
composer create-project --prefer-dist wanglelecc/laracms cms -vvv
```

安装好之后，修改 `.env` 配置数据库

## 执行迁移
```shell
php artisan migrate
php artisan db:seed
```

执行完就可以访问了（要先配置好虚拟主机）。
http://example.com/administrator

> 注：要先配置好数据库，默认用户: admin@56br.com / 123456

Github 地址 https://github.com/wanglelecc/laracms

## 捐赠
如果你觉得本项目给你带来了帮助，可以请作者喝一杯 [ 咖啡 ]

<p><img src="./public/images/pay.jpg"></p>

> 捐赠不代表提供有偿服务，望须知。
