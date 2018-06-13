# 技术汇总
汇总java生态圈常用技术框架、数据库、开源中间件、微服务、系统架构、团队管理、一线互联网公司架构案例等知识。

## 基础知识

## 进阶

## RDBMS

## NoSQL
* [Redis](https://redis.io/)
* [MongoDB](https://www.mongodb.com/)
* [HBase](http://hbase.apache.org/)
* [Elasticsearch](https://www.elastic.co/products/elasticsearch)

## 常用框架/第三方库
* Spring 全家桶
  - [Spring Framework](https://spring.io/projects/spring-framework)
  - [Spring Boot](https://spring.io/projects/spring-boot)
  - [Spring Cloud](https://spring.io/projects/spring-cloud)

* ORM 框架
  - [MyBatis](http://www.mybatis.org/mybatis-3/)
  - [Spring JDBC](https://spring.io/projects/spring-framework)
  - [DbUtils](https://commons.apache.org/proper/commons-dbutils/)

* Http 网络请求
  - [OkHttp](http://square.github.io/okhttp/)
  - [AsyncHttpClient](https://github.com/AsyncHttpClient/async-http-client)
  - [Apache HttpClient](http://hc.apache.org/httpcomponents-client-4.5.x/)

* JSON序列化\&反序列化
  - [jackson](http://wiki.fasterxml.com/JacksonHome)
  - [Google Gson](https://github.com/google/gson)
  - [Alibaba fastjson](https://github.com/alibaba/fastjson)

* 数据库连接池
  - [Alibaba druid](https://github.com/alibaba/druid)
  - [HikariCP](http://brettwooldridge.github.io/HikariCP/)
  - [c3p0](https://www.mchange.com/projects/c3p0/)
  - [DBCP](http://commons.apache.org/proper/commons-dbcp/)

* 日期\&时间处理
  - [Joda-Time](http://www.joda.org/joda-time/)

* Java 序列化框架
  - [Google Protobuf](http://developers.google.com/protocol-buffers/)
  - [Hessian](http://hessian.caucho.com/)
  - [Kryo](https://github.com/EsotericSoftware/kryo)
  - [protostuff](https://github.com/protostuff/protostuff)
  - [Fst](https://github.com/RuedigerMoeller/fast-serialization)

* 本地缓存
  - [Google Guava](https://github.com/google/guava)
  - [Caffeine](https://github.com/ben-manes/caffeine)

* 分布式缓存
  - [Jedis](https://github.com/xetorthio/jedis)
  - [Redisson](https://github.com/redisson/redisson)
  - [Ehcache](http://www.ehcache.org/)
  - [Hazelcast](https://hazelcast.com/)

* 任务调度框架
  - [Quartz](http://www.quartz-scheduler.org/)

* 字节码增强
  - [Javassist](http://jboss-javassist.github.io/javassist/)
  - [cglib](https://github.com/cglib/cglib)

* 服务熔断\&降级
  - [Hystrix](https://github.com/Netflix/Hystrix/)

* 服务注册\&发现
  - [Eureka](https://github.com/Netflix/eureka)
  - [Consul](https://www.consul.io/)
  - [etcd](https://coreos.com/etcd/)

* 分布式协调\&选主
  - [Apache Zookeeper](https://zookeeper.apache.org/)

* Zookeeper客户端库
  - [Apache Curator](http://curator.apache.org/)
  - [zkclient](https://github.com/sgroschupf/zkclient)

* NIO框架
  - [Netty](http://netty.io/)
  - [Grizzly]()
  - [Ver]()

* Bean 属性拷贝
  - [Dozer](http://dozer.sourceforge.net/)
  - [commons-beanutils](http://commons.apache.org/proper/commons-beanutils/)

* 其他
  - [Lomobok](https://www.projectlombok.org/)
  - [commons-codec](http://commons.apache.org/proper/commons-codec/)
  - [commons-lang3](https://commons.apache.org/proper/commons-lang/)

* 日志
  - [slf4j](https://www.slf4j.org/)
  - [logback](https://logback.qos.ch/)
  - [log4j2](https://logging.apache.org/log4j/2.x/)

* 单元测试
  - [JUnit 4](https://junit.org/junit4/)
  - [Mockito](http://site.mockito.org/)
  
## 中间件
* RPC框架
  - [阿里巴巴 dubbo](http://dubbo.io/)
  - [新浪微博 motan](https://github.com/weibocom/motan)
  - [Google gRPC](https://www.grpc.io/)
  - [蚂蚁金服 sofa-rpc](https://github.com/alipay/sofa-rpc)
  - [百度 brpc](https://github.com/brpc/brpc)
  - [腾讯 Tars](https://github.com/Tencent/Tars)

* MQ消息
  - [RabbitMQ](http://www.rabbitmq.com/)
  - [Apache Kafka](http://kafka.apache.org/)
  - [Apache ActiveMQ](http://activemq.apache.org/)
  - [Apache RocketMQ](https://rocketmq.apache.org/)

* 数据库Sharding
  - [阿里巴巴 Cobar](https://github.com/alibaba/cobar)
  - [淘宝 tddl](https://github.com/alibaba/tb_tddl)
  - [Mycat 数据库分库分表中间件](http://www.mycat.io/)
  - [sharding-jdbc](http://shardingjdbc.io/)
  - [mango](http://mango.jfaster.org/)

* 配置中心
  - [百度 disconf](https://github.com/knightliao/disconf)
  - [携程 apollo](https://github.com/ctripcorp/apollo)

* 分布式Job
  - [Elastic-Job](http://elasticjob.io/)
  - [TBSchedule](http://code.taobao.org/p/tbschedule/wiki/tbschedule-quick-start/)

* 分布式ID生成器
  - [ Twitter Snowflake](https://github.com/twitter/snowflake)
  - [百度 uid-generator](https://github.com/baidu/uid-generator)
  - [美团 Leaf](https://tech.meituan.com/MT_Leaf.html)

* 分布式文件系统
  - [FastDFS](https://github.com/happyfish100/fastdfs)

* 数据库binlog解析
  - [阿里巴巴 canal](https://github.com/alibaba/canal)

## 分布式
数据一致性、服务治理、服务降级

分布式事务
2PC、3PC、CAP、BASE、 可靠消息最终一致性、最大努力通知、TCC

## 微服务
SOA、康威定律

ServiceMesh
Docker & Kubernets
Spring Boot
Spring Cloud

## 安全

## 团队管理


## 架构设计
* [后端架构师技术图谱](https://github.com/xingshaocheng/architect-awesome)

## 互联网公司架构
* [互联网公司技术架构](https://github.com/davideuler/architecture.of.internet-product)
* [互联网公司架构: 淘宝技术架构，阿里巴巴技术架构](https://github.com/davideuler/architecture.taobao-alibaba)
* [互联网公司架构: 微信技术架构， 腾讯技术架构](https://github.com/davideuler/architecture.wechat-tencent)
* [互联网公司架构: 美团点评技术架构](https://github.com/davideuler/architecture.meituan-dianping)
