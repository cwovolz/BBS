# 区块链论坛项目

## 简介
本项目由前后台组成，前台实现了基本的论坛操作（登录，注册，轮播图，各个板块下的帖子显示，用户信息查看和修改，发帖，点赞，评论等功能），后台是CMS管理系统
主要实现了管理人员的权限分配和限制，个人信息查看和修改，前台板块管理，前台帖子管理，前台轮播图的管理等功能。是我学习flask时候练手项目

## 主要用到的技术
python3+flask框架，前端html+css+bootstrap框架+js+jq+ajax,前端弹窗用的是sweetalert2，注册界面短信验证码调用的是阿里大鱼短信接口，图形验证码是用
python中PIL图形处理工具画的，验证码缓存是用的memcache,用celery+redis来异步完成发送短信验证码和邮箱验证码操作，用户上传的图片调用的七牛接口等等

## 使用方法
* 克隆到本地
```
https://github.com/zjy959/BBS.git
```
