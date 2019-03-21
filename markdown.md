---
layout: markdown
title: ''
lang: 'en'
photo: 'assets/img/cvphoto.jpg'
contact:
  email: 'ximingliu_nk@hotmail.com'
  phone: '15620948548'
  github: 'takamachi'
---

# 刘希明
研发类

-----------

## 个人介绍


## 教育背景
2016.9-至今&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
南开大学&nbsp;&nbsp;&nbsp;&nbsp;
计算机学院，计算机科学与技术&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
硕士

2012.9-2016.6&nbsp;&nbsp;&nbsp;&nbsp;
南开大学&nbsp;&nbsp;&nbsp;&nbsp;
计算机与控制工程学院，计算机科学与技术&nbsp;&nbsp;&nbsp;&nbsp;
学士

## 技能

### 编程语言
* C++
* Python

### Skill Group
* Linux
* Docker
* LLVM
* QEMU

## 学术研究
### 嵌入式系统及虚拟化
#### 2018年5月 - 2018年10月
<details>
 <summary>虚拟化环境中线程级SLO保障的I/O软件框架研究</summary>
  对虚拟机的系统调用进行修改，使得I/O请求中可以携带必要的服务保障信息。扩展virtio协议，让携带的服务保障信息可以跨越虚拟机和宿主机之间的语义鸿沟。已被《计算机工程与科学》录用。
</details>

### Intel Software Guard Extensions（SGX）
#### 2018年9月 - 至今
<details>
 <summary>SGX底层页面管理机制分析及优化</summary>
  对SGX的底层页面管理机制进行了深入分析和性能测试。设计了一个全局LRU的页面交换算法来保障使用SGX的程序之间内存占用的公平性。在SGX的驱动中加入了启发式的页面预取算法，通过对程序触发的Page fault异常的访存行为进行分析来决定是否进行预取以及预取页面的地址。学习并熟练使用SPEC CPU2017测试工具，并使用LLVM对SPEC中的benchmark进行静态分析，寻找可以认定为连续访存的区域。使用LLVM在较大的连续访存中自动插入对SGX驱动的提示，让SGX可以根据这些提示对页面进行预取。
</details>


## 工程项目

### 基于ARM的远程控制及软件开发
#### 2017年10月 - 2018年10月
采用基于ARM指令集的树莓派3和传感器芯片以及光谱仪设备，完成温度，湿度，GPS数据采集，光谱仪数据采集，音频采集，照片及视频采集等功能。与服务器建立websocket连接，根据服务器发送的采集命令来完成对应的数据采集操作，并将采集到的数据上传服务器。

### Elasticsearch环境部署及身份验证系统的搭建
#### 2017年7月 - 2017年11月
使用docker完成特定环境下Elasticsearch的部署。使用Searchguard插件为Elasticsearch添加账户管理系统，为不同的账户分别赋予访问，查询，插入，删除等权限来实现不同等级用户的管理。

## 其他
### 英语
CET6，曾参与过《嵌入式计算系统设计原理》的翻译工作，可以熟练阅读专业相关文献
### 个人奖项
南开大学学业奖学金

