## 前言

随着新冠疫情的蔓延，学校作为人员密集场所，疫情防控工作显得尤为重要。本团队为此开发了“校园疫情防控管理平台小程序+SpringBoot”，旨在帮助学校实现疫情的快速响应和智能化管理。以下是该项目的基本介绍。

## 内容介绍

本项目是一款基于微信小程序的校园疫情防控管理平台，主要功能包括：健康状况上报、行程追踪、防疫知识宣传、实时疫情动态等。通过该平台，学校可以及时了解学生健康状况，做好疫情防控工作。同时，学生也可以便捷地完成每日健康上报，共同维护校园安全。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为项目中的一段核心代码，展示了如何通过MyBatis实现健康状况的上报功能：

```java
// Mapper接口
public interface HealthReportMapper {
    @Insert("INSERT INTO health_report(user_id, temperature, health_status, report_time) VALUES(#{userId}, #{temperature}, #{healthStatus}, #{reportTime})")
    void insertHealthReport(HealthReport healthReport);
}

// Service层
@Service
public class HealthReportService {
    @Autowired
    private HealthReportMapper healthReportMapper;

    public void addHealthReport(HealthReport healthReport) {
        healthReportMapper.insertHealthReport(healthReport);
    }
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
![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/341832/4/3193/231255/68c6381bFe07db636/0b1ff65f161cd74f.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/332417/6/13191/19252/68c637f2F2f66b11a/9d935cf2a1ae1d05.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/323366/33/20098/65271/68c637f3Fe90eff89/db600d30f9a77844.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/345786/22/3117/33883/68c637f3Fa321c2d9/bf924055c92fe14d.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/333948/8/13223/17285/68c637f3F8ea61bb9/1e97c24253bb52ca.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/347783/34/3135/25822/68c637f3Ff032e1d8/110bdb0dc5f34828.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/349915/35/3235/59215/68c637f4F73181395/ad3a8ecdeff8f321.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/338760/18/10600/58321/68c637f4Feabbe4c2/5b77e289a9bd5a90.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/334603/1/13062/28502/68c637f4F0fc15639/4e89ffd53a58413d.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/325895/28/19761/29056/68c637f4Fdf6cc396/bb07dd170e063012.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
