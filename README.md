## Java架构师--成神之路

#### 修改记录
| 版本        | 编写时间   |  作者  | 描述  |
| --------   | -----:  | :----:  |:----:  |
| v1.0.0      | 2019-10-29  |   Rock.Sang    |  梳理大纲   |


#### 文章目录

- [第一章 基础篇](#第一章-基础篇 )
   - [1.1 集合容器](#集合容器)
   - [1.2 数据结构](#数据结构)
   - [1.3 常用算法](#常用算法)
   - [1.4 JDK演变](#jdk演变)
   - [1.5 I/O机制](#i/o机制)
   - [1.6 网络协议](#网络协议)
- [第二章 进阶篇](#第二章-进阶篇 )
   - [2.1 类加载](#类加载)
   - [2.2 JVM](#jvm)
   - [2.3 垃圾回收](#垃圾回收)
   - [2.4 线程](#线程)
   - [2.5 线程池](#线程池)
   - [2.6 锁](#锁)
- [第三章 中间件篇](#第三章-中间件篇 )
   - [3.1 缓存](#缓存)
   - [3.2 远程调用](#远程调用)
   - [3.3 消息队列](#消息队列)
   - [3.4 任务调序](#任务调序)
   - [3.5 搜索引擎](#搜索引擎)
   - [3.6 分布式锁](#分布式锁)
   - [3.7 监控](#监控)
   - [3.8 日志监控](#日志监控)
   - [3.9 限流&熔断](#限流&熔断)
   - [3.10 分库分表](#分库分表)
- [第四章 架构设计篇](#第四章-架构设计篇 )
   - [4.1 系统设计](#系统设计)    
     - [4.1.1 UML](#UML)    
     - [4.1.2 流程图](#流程图)    
     - [4.1.3 领域模型](#领域模型)    
   - [4.2 权限认证](#权限认证)    
- [第五章 设计模式篇](#第五章-设计模式篇 )
   - [5.1 设计模式的分类](#设计模式的分类) 
   - [5.2 设计模式的六大原则](#设计模式的六大原则) 
   - [5.3 常用设计模式](#常用设计模式) 
- [第六章 框架篇](#第六章-框架篇 )
   - [6.1 Spring框架](#Spring框架)       
   - [6.2 分布式框架](#分布式框架)       
   - [6.3 SpringBoot框架](#SpringBoot框架)       
   - [6.4 SpringCloud框架](#SpringCloud框架)       
- [第七章 数据库篇](#第七章-数据库篇 )
   - [7.1 Mysql](#Mysql)       
   - [7.2 索引](#索引)       
- [第八章 源码篇](#第八章-源码篇 )
   - [8.1 Spring源码](#Spring源码)       
   - [8.2 Mybatis源码](#Mybatis源码)       
   - [8.3 Dubbo源码](#Dubbo源码)       
   - [8.4 Netty源码](#Netty源码)       
   - [8.5 ZooKeeper源码](#ZooKeeper源码)       
- [第九章 大数据篇](#第九章-大数据篇 )
   - [9.1 Storm，spark和流式计算](#Storm和spark和流式计算) 
   - [9.2 Hadoop，离线计算](#Hadoop和离线计算) 
   - [9.3 HDFS、MapReduce](#HDFS和MapReduce) 
- [第十章 深度/机器学习篇](#第十章-深度和机器学习篇 )
- [第十一章 面试篇](#第十一章-面试篇 )
   - [11.1 备战面试](#备战面试) 
   - [11.2 常见面试题总结](#常见面试题总结) 
   - [11.3 面经](#面经) 
- [第十二章 工具篇](#第十二章-工具篇)
   - [12.1 常用IDE](#常用IDE)    
   - [12.2 Git](#Git)    
- [第十三章 项目实战篇](#第十三章-项目实战篇)
   - [13.1 支付系统架构图](#支付系统架构图)   
   - [13.2 收银系统架构图](#收银系统架构图)   
   - [13.3 发票系统架构图](#发票系统架构图)   
- [第十四章 资源篇](#第十四章-资源篇)
   - [14.1 书单](#书单)  
   - [14.2 Github榜单](#Github榜单)  
   - [14.3 Blog榜单](#Blog榜单)  
- [第十五章 技术管理](#第十五章-技术管理) 
 
      

## 第一章 基础篇

#### 集合容器

* [1.1.1 Java 基础知识回顾](docs/part1-basics/1-1-1%20Java基础知识.md)
* [1.1.2 集合类](docs/part1-basics/1-1-2%20集合.md)
* [1.1.3 ArrayList源码学习](docs/part1-basics/1-1-3%20ArrayList源码学习.md)
* [1.1.4 LinkedList源码学习](docs/part1-basics/1-1-4%20LinkedList源码学习.md)
* [1.1.5 HashMap源码学习](docs/part1-basics/1-1-5%20HashMap源码学习.md)
* [1.1.6 HashTable源码学习](docs/part1-basics/1-1-6%20HashTable源码学习.md)
* [1.1.7 ConcurrentHashMap源码学习](docs/part1-basics/1-1-7%20ConcurrentHashMap源码学习.md)

#### 数据结构

* [1.2.1 数组](docs/part1-basics/1-2-1%20数组.md)
* [1.2.2 链表](docs/part1-basics/1-2-2%20链表.md)
* [1.2.3 队列](docs/part1-basics/1-2-3%20队列.md)
* [1.2.4 树](docs/part1-basics/1-2-4%20树.md)
* [1.2.5 堆和栈](docs/part1-basics/1-2-5%20堆和栈.md)
* [1.2.6 散列表](docs/part1-basics/1-2-6%20散列表.md)
* [1.2.7 图](docs/part1-basics/1-2-7%20图.md)

#### 常用算法

* [1.3.1 几种常用排序算法](docs/part1-basics/1-3-1%20几种常用排序算法.md)
* [1.3.2 几种常用查找算法](docs/part1-basics/1-3-2%20几种常用查找算法.md)

#### JDK演变

* [1.4.1 Java8新特性](docs/part1-basics/1-4-1%20Java8新特性.md)
* [1.4.2 Java9新特性](docs/part1-basics/1-4-2%20Java9新特性.md)
* [1.4.3 Java10+新特性](docs/part1-basics/1-4-3%20Java10+新特性.md)

#### I/O机制

* [1.5.1 I/O工作机制](docs/part1-basics/1-5-1%20IO工作机制.md)

#### 网络协议

* [1.6.1 网络分层结构](docs/part1-basics/1-6-1%20网络分层结构.md)
* [1.6.2 三次握手和四次挥手](docs/part1-basics/1-6-2%20三次握手和四次挥手.md)

## 第二章 进阶篇

#### 类加载

#### JVM

#### 垃圾回收

#### 线程

#### 线程池

#### 锁 


## 第三章 中间件篇

#### 缓存

#### 远程调用

#### 消息队列

#### 任务调序

#### 搜索引擎

#### 分布式锁

#### 监控

#### 日志监控

#### 限流&熔断

#### 分库分表


## 第四章 架构设计篇

#### 系统设计

##### UML

##### 流程图

##### 领域模型

#### 权限认证


## 第五章 设计模式篇

#### 设计模式的分类

#### 设计模式的六大原则

#### 常用设计模式



## 第六章 框架篇

#### Spring框架

#### 分布式框架

#### SpringBoot框架

#### SpringCloud框架


## 第七章 数据库篇

#### Mysql

#### 索引


## 第八章 源码篇

#### Spring源码

#### Mybatis源码

#### Dubbo源码

#### Netty源码

#### ZooKeeper源码


## 第九章 大数据篇

#### Storm和spark和流式计算

#### Hadoop和离线计算

#### HDFS和MapReduce



## 第十章 深度和机器学习篇

#### 智能时代

## 第十一章 面试篇

#### 备战面试

#### 常见面试题总结

#### 面经


## 第十二章 工具篇

#### 常用IDE

#### Git


## 第十三章 项目实战篇

#### 支付系统架构图

#### 收银系统架构图

#### 发票系统架构图


## 第十四章 资源篇

#### 书单

#### Github榜单

#### Blog榜单


## 第十五章 技术管理


