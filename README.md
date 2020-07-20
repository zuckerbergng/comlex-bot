# QQ-打卡机器人
> ​    使用了 Nonebot 框架，采用了异步的操作。可以对群聊信息可以做出及时反馈，同时实现了对私聊消息的某些~~（无关紧要的）~~操作

[![Python Version](https://camo.githubusercontent.com/033fcb6e9f5284026c32cdc1545ef23d1d6c9c83/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707974686f6e2d332e372b2d626c75652e737667)](https://camo.githubusercontent.com/033fcb6e9f5284026c32cdc1545ef23d1d6c9c83/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707974686f6e2d332e372b2d626c75652e737667) [![CQHTTP Version](https://camo.githubusercontent.com/d1e38a183342e443ed99f21d061aaac532683354/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6371687474702d342e382b2d626c61636b2e737667)](https://camo.githubusercontent.com/d1e38a183342e443ed99f21d061aaac532683354/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6371687474702d342e382b2d626c61636b2e737667)

## 简介

实现了：
-  [x]  打卡活动

>详细操作：
>1、若要参加打卡活动，首先对机器人发送“我要参加打卡”
>2、每日可以打卡两门课---高数和英语
>3、可以查看当前打卡所获得的积分

-  [x]  每日一句和每日英语好句

>发送“每日一句"或者“英语美句”，即可获得。

-  [ ]  每周对积分进行排行

>暂时还没有得到实现



## 设计

**1、使用Nonebot框架接收并处理消息，由于python的装饰器功能，仅需要专注于功能模块的设计即可。**

**2、与 MySQL 数据库连接，采用SQLAlchemy对数据进行 增加、查询以及更新操作，整个数据库是BC范式**


