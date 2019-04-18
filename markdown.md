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

## 教育背景
2017.9-至今&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
南开大学&nbsp;&nbsp;&nbsp;&nbsp;
计算机学院，计算机科学与技术&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
硕士

主要课程：计算机网络技术，高级计算机体系结构，并行计算技术，计算机算法设计与分析，模式识别，WEB大数据挖掘

多次获得南开大学学业奖学金

2013.9-2017.6&nbsp;&nbsp;&nbsp;&nbsp;
南开大学&nbsp;&nbsp;&nbsp;&nbsp;
计算机与控制工程学院，智能科学与技术 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
学士

主要课程：高级语言程序设计（C++）, 数据结构，操作系统，计算机组成原理，数字电子技术，模拟电子技术，自动控制原理，概率论与数理统计

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
  对SGX的底层页面管理机制进行了深入分析和性能测试。设计了一个全局LRU的页面交换算法来保障使用SGX的程序之间内存占用的公平性。在SGX的驱动中加入了启发式的页面预取算法，通过对程序触发的Page fault异常的访存行为进行分析来决定是否进行预取以及预取页面的地址。通过页面预取来提高SGX的访存性能。
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
### 专业技能
熟练使用编程语言C/C++/Python
熟练使用Linux
了解Docker, LLVM, QEMU等相关技术
