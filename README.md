# 前言

随着信息技术的发展，互联网医疗逐渐深入人们的生活。儿童预防接种预约微信小程序正是基于这样的背景而诞生，旨在为家长们提供一个便捷、高效的疫苗接种预约平台。本项目使用Spring Boot技术构建后端，结合微信小程序实现前端展示，以下为详细的项目介绍。

## 内容介绍

本项目主要实现了儿童预防接种预约的基本功能，包括：用户注册登录、疫苗信息查看、预约接种时间、接种提醒等。系统采用了模块化设计，方便后期功能的扩展与维护。通过微信小程序，用户可以随时随地查看疫苗信息，预约接种时间，极大的提高了家长们的接种体验。

## 技术介绍

### 语言：Java
### 使用框架：
- Spring
- Springmvc
- Mybatis
- 微信小程序

### 前端技术：
- JS
- Vue
- CSS3
- Uniapp

### 开发工具：
- IDEA/Eclipse
- Uniapp

### 数据库：
- MySQL 5.7/8.0

### 数据库管理工具：
- phpstudy/Navicat

### JDK版本：
- jdk1.8

### Maven:
- apache-maven 3.8.1-bin

### 前端环境：
- Node.Js 12\14\16

## 核心代码

以下为项目中的一部分核心代码，展示了如何使用MyBatis进行疫苗信息的查询。

```java
// VaccineMapper.java
public interface VaccineMapper {
    @Select("SELECT * FROM vaccine WHERE id = #{id}")
    Vaccine selectVaccineById(int id);
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
![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/333708/20/12599/178702/68c4df9fF4a335c6d/fbb6b7d9d2e40fbe.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/335969/11/10270/25866/68c4df77F82847dbf/3d5493e074524c18.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/344207/8/1639/66270/68c4df77F7f205e04/a958c6d0a17caed4.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/345599/24/2795/50009/68c4df78F78493e0a/32c3201a405a463e.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/323814/2/19592/24328/68c4df78Fb36cd75a/d9e6ce4d3ecb60a4.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/346066/21/2793/55488/68c4df78F53c16e81/7c09a83261eeef19.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/349549/34/2810/21970/68c4df78F7e6b809a/cd08cb4b315d10b2.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/333759/37/12724/16098/68c4df78Fc9cac91b/d2bef45dc04ec887.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/347039/32/2848/19914/68c4df78Fd90bf22a/926f9d9e1dd344a1.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/330821/8/12709/21732/68c4df79F402250b3/cae525cb393dd1e5.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
