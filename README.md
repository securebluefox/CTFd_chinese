![](https://github.com/CTFd/CTFd/blob/master/CTFd/themes/core/static/img/logo.png?raw=true)
====

[![Build Status](https://travis-ci.org/CTFd/CTFd.svg?branch=master)](https://travis-ci.org/CTFd/CTFd)
[![CTFd Slack](https://slack.ctfd.io/badge.svg)](https://slack.ctfd.io/)

## 什么是CTFd？ 

CTFd是一个Capture The Flag框架，主要关注易用性和可定制性。 它提供了运行CTF所需的一切，并且可以使用插件和主题轻松进行自定义。 

![CTFd is a CTF in a can.](https://github.com/CTFd/CTFd/blob/master/CTFd/themes/core/static/img/scoreboard.png?raw=true)

## 特性 

 * 从管理界面创建您自己的题目，类别，提示和标志 
    * 基于静态和正则表达式的flags
    * 用户可以免费或使用积分解锁提示 
    * 文件上传到服务器或[Amazon S3](https://github.com/CTFd/CTFd-S3-plugin)
    * 限制题目尝试次数并隐藏题目 
    * 自动提交限制 
 * 记分牌与自动分辨率 
    * 向选手隐藏成绩 
    * 在特定时间冻结分数 
    * [动态积分](https://github.com/CTFd/DynamicValueChallenge)
 * 积分图表比较前10名队伍和队伍得分图 
 * Markdown内容管理系统 
 * SMTP + Mailgun电子邮件支持 
    * 支持电子邮件确认 
    * 支持忘记密码找回
 * 自动开始和结束比赛
 * 队伍管理和隐藏 
 * 使用[插件](https://github.com/CTFd/CTFd/wiki/Plugins)和 [主题](https://github.com/CTFd/CTFd/tree/master/CTFd/themes)界面自定义所有内容 
 * 导入和导出CTF数据用于归档 
 * 还有更多... 

## 安装
  1. 运行 `./prepare.sh` 以使用apt来安装依赖关系。 
  2. 根据自己的喜好修改[CTFd/config.py](https://github.com/CTFd/CTFd/blob/master/CTFd/config.py)
  3. 使用 `flask run` 以在终端中进入调试模式。 

或者您可以使用以下命令使用Docker： 

`docker run -p 8000:8000 -it ctfd/ctfd`

 * [这里](https://github.com/CTFd/CTFd/wiki/Basic-Deployment) 有一些部署选项 

 * 您可以查看[“入门指南”](https://github.com/CTFd/CTFd/wiki/Getting-Started)，了解入门所需的一些功能的细分。 

   译者注：https://blog.csdn.net/CoolD_/article/details/75674933讲的还是不错的

##现场演示 

https://demo.ctfd.io/

## 支持 

要获得基本支持，您可以加入  [CTFd Slack Community](https://slack.ctfd.io/): [![CTFd Slack](https://slack.ctfd.io/badge.svg)](https://slack.ctfd.io/)

如果您更喜欢商业支持或有特殊项目，请发邮件给我们：  [support@ctfd.io](mailto:support@ctfd.io).

## 托管主机 

希望使用CTFd但不想处理基础设施管理？ 查看CTFd网站以了解托管的CTFd部署。 

## HackerFire
你想寻找CTF题目去练习？ [HackerFire](https://hackerfire.com/)是使用CTFd构建的学习型CTF。 它具有各种各样的挑战，并经常更新新内容。 它还包含自定义知识资源，可以向新手讲授用于解决挑战的技术。 

##版权

 * Logo by [Laura Barbera](http://www.laurabb.com/)
 * Theme by [Christopher Thompson](https://github.com/breadchris)
 * 汉化作者：土豆豆的小黏黏
