## 前言

欢迎来到基于SSM的游戏攻略发布系统项目。这是一个旨在为广大游戏爱好者提供便捷、高效的游戏攻略分享平台。通过本系统，用户可以轻松发布、浏览和讨论各类游戏攻略，共同进步，享受游戏的乐趣。

## 内容介绍

本项目主要分为以下几个模块：攻略发布、攻略浏览、攻略评论、用户管理等。攻略发布模块允许用户快速发布自己的游戏攻略，支持富文本编辑，让攻略更具可读性。攻略浏览模块为用户提供丰富的攻略资源，方便用户查找所需内容。攻略评论模块则让用户可以互相讨论、交流游戏心得。此外，用户管理模块为用户提供个人信息管理功能，确保系统安全稳定运行。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Springmvc、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是攻略发布模块的部分核心代码：

```java
// Controller层
@RequestMapping("/publish")
public String publish(GameGuide gameGuide, HttpSession session) {
    User user = (User) session.getAttribute("user");
    if (user == null) {
        return "redirect:/login";
    }
    gameGuide.setUser(user);
    gameGuideService.saveGameGuide(gameGuide);
    return "redirect:/guideList";
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/339905/35/1681/200709/68acadedFcc48c122/274b785ccf837641.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/332317/19/4199/60731/68acadcdFc161c175/fb21b29ff3c32d50.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328932/5/10892/145611/68acadcdF39de2339/5839fa9891091f5d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/339334/2/1723/71369/68acadceF757d8ca1/db61e4a15373108b.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340701/31/1706/69461/68acadceF84c3f075/2124f3267727a7a9.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/328398/20/11022/36136/68acadcfF9eef2548/5232354db29bc8dd.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/334482/3/4243/55852/68acadcfF135cc0e4/3b8ef5df59ac1073.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/331872/10/4054/33286/68acadcfF57444604/6b4ec87c7ba5f683.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/294762/21/16889/98059/68acadd0F70489425/2b54dd73b3fa734a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/329523/11/4313/35388/68acadd0F6f6d39c2/47e434976e993fef.jpg)

