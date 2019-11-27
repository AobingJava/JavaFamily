作为一个在互联网公司面一次拿一次Offer的面霸，打败了无数竞争对手，每次都只能看到无数落寞的身影失望的离开，略感愧疚（**请允许我使用一下夸张的修辞手法**）。

在一个寂寞难耐的夜晚，我痛定思痛，决定开始写《**吊打面试官**》系列，希望能帮助各位读者以后面试势如破竹，对面试官进行360°的反击，吊打问你的面试官，让一同面试的同僚瞠目结舌，疯狂收割大厂**Offer**！

我会从下图中的知识点去写这个系列，很多细节的点，可能想得不是很完善，大家可以去[【公众号】](#公众号)获取或者加我[【微信】](#微信)提意见(别忘记**Star**哟)。

**Git**跟**公众号**同步更新**每周最少两篇**，公众号首发，比博客早一到两篇.
<p align="center">
<a href="https://github.com/AobingJava/JavaFamily" target="_blank">
	<img src="https://tva1.sinaimg.cn/large/006y8mN6ly1g98588lrx2j305k05kgm0.jpg" width=""/>
</a>
</p>

<p align="center">
  <a href="#目录"><img src="https://img.shields.io/badge/阅读-read-brightgreen.svg" alt="阅读"></a>
  <a href="#微信"><img src="https://img.shields.io/badge/chat-微信群-blue.svg" alt="微信群"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-JavaFamily-lightgrey.svg" alt="公众号"></a>
  <a href="https://juejin.im/user/59b416065188257e671b670a"><img src="https://img.shields.io/badge/博客-掘金-important.svg" alt="公众号"></a>
  <a href="https://me.csdn.net/qq_35190492"><img src="https://img.shields.io/badge/博客-CSDN-critical.svg" alt="投稿"></a>
  <a href="https://www.cnblogs.com/aobing/"><img src="https://img.shields.io/badge/博客-博客园-important" alt="投稿"></a>
</p>

![](https://tva1.sinaimg.cn/large/006y8mN6ly1g93ffaeoanj30u02ejqep.jpg)
<a name="目录">目录</a>

- Java基础核心串讲
  - 计算机操作系统与Linux
  - 计算机网络
  - 7种常见的设计模式和使用场景
  - Java必会基础与新版本特性

- 深入浅出JVM

  - JVM内存模型
  - 性能调优、线上问题排查
  - 类加载机制详解
  - 垃圾回收机制
  - 垃圾回收器、垃圾回收算法

- 并发与多线程

  - 线程状态转换与通信机制
  - 线程同步与互斥
  - 线程池知识点
  - 常见的JUC工具类

- 常用工具集

  - JVM问题排查工具-JMC
  - IDEA开发神器
  - 线上调试神器-btrace
  - Git原理与工作流
  - Linux常用分析工具

- 数据结构与算法

  - 从二叉搜索树到B+树
  - 经典问题之字符串
  - 经典问题之TOPK

- 必会框架

  - Spring全家桶以及源码分析

  - 高性能NIO框架-Netty
  - 分布式框架基石-RPC
  - ORM框架Mybatis源码分析

- [高并发架构基石-缓存](https://github.com/AobingJava/JavaFamily/tree/master/docs/redis)

  - [Redis基础知识](https://github.com/AobingJava/JavaFamily/blob/master/docs/redis/Redis%E5%9F%BA%E7%A1%80.md)
  - [缓存击穿、雪崩、穿透](https://github.com/AobingJava/JavaFamily/blob/master/docs/redis/%E7%BC%93%E5%AD%98%E5%87%BB%E7%A9%BF%E3%80%81%E9%9B%AA%E5%B4%A9%E3%80%81%E7%A9%BF%E9%80%8F.md)
  - [集群高可用、哨兵、持久化、LRU](https://github.com/AobingJava/JavaFamily/blob/master/docs/redis/%E9%9B%86%E7%BE%A4%E9%AB%98%E5%8F%AF%E7%94%A8%E3%80%81%E5%93%A8%E5%85%B5%E3%80%81%E6%8C%81%E4%B9%85%E5%8C%96%E3%80%81LRU.md)
  - [分布式锁、并发竞争、双写一致性](https://github.com/AobingJava/JavaFamily/blob/master/docs/redis/%E5%88%86%E5%B8%83%E5%BC%8F%E9%94%81%E3%80%81%E5%B9%B6%E5%8F%91%E7%AB%9E%E4%BA%89%E3%80%81%E5%8F%8C%E5%86%99%E4%B8%80%E8%87%B4%E6%80%A7.md)
  - [Redis常见面试题](https://github.com/AobingJava/JavaFamily/blob/master/docs/redis/Redis%E5%B8%B8%E8%A7%81%E9%9D%A2%E8%AF%95%E9%A2%98.md)
  - [布隆过滤器(BloomFilter)](https://github.com/AobingJava/JavaFamily/blob/master/docs/redis/%E5%B8%83%E9%9A%86%E8%BF%87%E6%BB%A4%E5%99%A8(BloomFilter).md)
  - [秒杀系统设计](https://github.com/AobingJava/JavaFamily/blob/master/docs/redis/%E7%A7%92%E6%9D%80%E7%B3%BB%E7%BB%9F%E8%AE%BE%E8%AE%A1.md)
  - [课代表总结](https://github.com/AobingJava/JavaFamily/blob/master/docs/redis/%E8%AF%BE%E4%BB%A3%E8%A1%A8%E6%80%BB%E7%BB%93.md)
- [消息队列](https://github.com/AobingJava/JavaFamily/tree/master/docs/mq)
  - [消息队列基础知识](https://github.com/AobingJava/JavaFamily/blob/master/docs/mq/%E6%B6%88%E6%81%AF%E9%98%9F%E5%88%97%E5%9F%BA%E7%A1%80.md)
  - [消息重复消费、分布式事务、顺序消费](https://github.com/AobingJava/JavaFamily/blob/master/docs/mq/%E9%87%8D%E5%A4%8D%E6%B6%88%E8%B4%B9%E3%80%81%E9%A1%BA%E5%BA%8F%E6%B6%88%E8%B4%B9%E3%80%81%E5%88%86%E5%B8%83%E5%BC%8F%E4%BA%8B%E5%8A%A1.md)
  - Kafka架构与原理
  - RocketMQ
  - 分布式事务

- 数据库

  - MySQL
  - 索引、锁机制
  - 事务特性、隔离级别
  - MySQL调优与最佳实践

- 大数据

  - ODPS离线分析
  - 搜索引擎组合 ElasticSearch、Canal、Kibana
  - Hive

- 架构演进之路

  - 从All in one 到微服务
  - 互联网架构之路
  - 怎么设计一个能顶住双十一的系统？

- 互联网前沿技术

  - 容器化：Docker与k8s详解

- 面试技巧

  - 简历
  - 语言组织
  - 加分项
  - 扬长避短
 # <a name="微信">联系我</a>
添加我的微信备注 " **git** "， 即可加入人才交流群，说实话在这个群，哪怕您不说话，光看聊天记录，都能学到东西。

Java3y作者，美团王炸，美团孔明，木子李，拼多多，阿里等大牛都在。

我有空也会跟大家一起交流每期写作的思路，以及倾听大家意见，周末有空可以问我**面经**和**职业规划答疑**。
 
( **公众号也记得关注下面有二维码↓** )。


![](https://user-gold-cdn.xitu.io/2019/11/15/16e6f8b7d0770411?w=250&h=324&f=png&s=63033)
 # <a name="公众号">公众号</a>
如果大家想要实时关注我更新的文章以及分享的干货的话，可以关注我的公众号(比博客更新早一到两篇)，求分享给身边的朋友。


![](https://user-gold-cdn.xitu.io/2019/11/15/16e6f8d625551f36?w=250&h=250&f=png&s=59017)

# 赞赏码

熬夜不易，觉得有很大帮助的朋友可以赏杯咖啡(**不接受学生赞赏**)，赏了一定要加我微信跟我说。

![](https://user-gold-cdn.xitu.io/2019/11/15/16e6f8c9f4d3b9bc?w=250&h=250&f=png&s=38901)

# 关于我
今年23岁，来自贵州遵义，大三学分提前休满的情况，在某为某阿里系电商任职过，现在在蘑菇街算法工程部门。

对很多场景比初学者可能熟悉一点，职场我也是个新手，很多知识点也是不是很清楚，不过有过很多面试经验，觉得把知识点用自己的风格展示给大家，希望大家能学到东西，我们一起进步。

**很希望跟大家分享职场的一路，觉得我不错也记得分享给身边的朋友哟。**
# 岗位内推
找所有职位比较出色的朋友，觉得合适的给我简历我可以内推，阿里 美团 蘑菇街 平多多 字节跳动 腾讯 等都可以.
# 鸣谢列表

以下排名不分先后!

<a href="https://github.com/simpleTo">
    <img src="https://avatars3.githubusercontent.com/u/24934495?s=400&v=4" width="45px"></a>
    
<a href="https://github.com/programes">  
    <img src="https://avatars3.githubusercontent.com/u/6359325?s=400&v=4" width="45px">
</a>
<a href="https://github.com/bertChen812">  
    <img src="https://avatars3.githubusercontent.com/u/37893362?s=400&v=4" width="45px">
</a>
<a href="https://github.com/cyberwave">
    <img src="https://avatars2.githubusercontent.com/u/7488935?s=400&v=4" width="45px"></a>
    
    
<a href="https://github.com/Gene1994">
    <img src="https://avatars3.githubusercontent.com/u/24930369?s=460&v=4" width="45px">
</a>
<a href="https://github.com/bertChen812">
    <img src="https://avatars0.githubusercontent.com/u/12581996?s=460&v=4" width="45px"></a>
<a href="https://github.com/illusorycloud">
    <img src="https://avatars3.githubusercontent.com/u/31980412?s=460&v=4" width="45px">
</a>
<a href="https://github.com/LiWenGu">
    <img src="https://avatars0.githubusercontent.com/u/15909210?s=460&v=4" width="45px">
</a>
<a href="https://github.com/kinglaw1204">
    <img src="https://avatars1.githubusercontent.com/u/20039931?s=460&v=4" width="45px">
</a>
<a href="https://github.com/jun1st">
    <img src="https://avatars2.githubusercontent.com/u/14312378?s=460&v=4" width="45px">
</a>"
<a href="https://github.com/fantasygg">  
    <img src="https://avatars3.githubusercontent.com/u/13445354?s=460&v=4" width="45px">
</a>
<a href="https://github.com/debugjoker">  
    <img src="https://avatars3.githubusercontent.com/u/26218005?s=460&v=4" width="45px">
</a>
<a href="https://github.com/zhyank">  
    <img src="https://avatars0.githubusercontent.com/u/17696240?s=460&v=4" width="45px">
</a>
<a href="https://github.com/Goose9527">  
    <img src="https://avatars2.githubusercontent.com/u/43314997?s=460&v=4" width="45px">
</a>
<a href="https://github.com/yuechuanx">  
    <img src="https://avatars3.githubusercontent.com/u/19339293?s=460&v=4" width="45px">
</a>
<a href="https://github.com/cnLGMing">  
    <img src="https://avatars2.githubusercontent.com/u/15910705?s=460&v=4" width="45px">
</a>
<a href="https://github.com/fanchenggang">  
    <img src="https://avatars0.githubusercontent.com/u/20358122?s=460&v=4" width="45px">
</a>

 