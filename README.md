# 技术汇总
汇总java生态圈常用技术框架、数据库、开源中间件、微服务、系统架构、线上问题定位&处理、团队管理、书单推荐、一线互联网公司架构案例等知识。

## 基础知识
* Java基础知识
* Java并发编程
* 数据结构与算法

## 进阶篇
* JDK源码阅读
* 框架知识
* JVM/类加载机制
* 设计模式

## 高级篇
* 性能优化
* 线上问题定位

## 常用框架\&第三方库
* [Spring](https://spring.io/) 全家桶
  - [Spring Framework](https://spring.io/projects/spring-framework) 推荐指数: ★★★★★
  - [Spring Boot](https://spring.io/projects/spring-boot) 推荐指数: ★★★★★
  - [Spring Cloud](https://spring.io/projects/spring-cloud) 推荐指数: ★★★★☆

* Web框架
  - [Spring Web MVC](https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html) 推荐指数: ★★★★★
  - [Spring WebFlux](https://docs.spring.io/spring/docs/5.0.0.BUILD-SNAPSHOT/spring-framework-reference/html/web-reactive.html)
  - [Struts 2【不推荐 安全漏洞太多】](https://struts.apache.org/) 推荐指数: ★★☆☆☆
  - [paoding-rose](http://www.54chen.com/rose.html)
  - [Blade](https://github.com/lets-blade/blade)
  - [JFinal](https://github.com/jfinal/jfinal)
  
* ORM 框架
  - [MyBatis](http://www.mybatis.org/mybatis-3/) 推荐指数: ★★★★☆
  - [Hibernate](http://hibernate.org/) ★★★★☆
  - [Spring JDBC](https://spring.io/projects/spring-framework) 推荐指数: ★★★★☆
  - [Spring Data JPA](https://projects.spring.io/spring-data-jpa/) 推荐指数: ★★★★☆
  - [jOOQ](https://www.jooq.org/) ★★★★☆
  - [DbUtils](https://commons.apache.org/proper/commons-dbutils/)

* Http 网络请求
  - [OkHttp](http://square.github.io/okhttp/) 推荐指数: ★★★★★
  - [AsyncHttpClient](https://github.com/AsyncHttpClient/async-http-client)
  - [Apache HttpClient](http://hc.apache.org/httpcomponents-client-4.5.x/)

* JSON library
  - [jackson](http://wiki.fasterxml.com/JacksonHome)
  - [Google Gson](https://github.com/google/gson)
  - [Alibaba fastjson](https://github.com/alibaba/fastjson)
  - [Square Moshi](https://github.com/square/moshi)

* 数据库连接池
  - [Alibaba druid](https://github.com/alibaba/druid) 推荐指数: ★★★★★
  - [HikariCP](http://brettwooldridge.github.io/HikariCP/) 推荐指数: ★★★★★
  - [c3p0](https://www.mchange.com/projects/c3p0/) 推荐指数: ★★★★☆
  - [DBCP](http://commons.apache.org/proper/commons-dbcp/) 推荐指数: ★★★★☆
  - [Tomcat JNDI Datasource](http://tomcat.apache.org/tomcat-8.5-doc/jndi-datasource-examples-howto.html) 推荐指数: ★★★★☆
  
* 日期\&时间处理
  - [Joda-Time](http://www.joda.org/joda-time/) 推荐指数: ★★★★★
  - [Java 8 Date/Time API](http://www.oracle.com/technetwork/articles/java/jf14-date-time-2125367.html)

* Java 序列化框架
  - [Protobuf](http://developers.google.com/protocol-buffers/)
  - [Hessian](http://hessian.caucho.com/)
  - [Kryo](https://github.com/EsotericSoftware/kryo)
  - [protostuff](https://github.com/protostuff/protostuff)
  - [fst](https://github.com/RuedigerMoeller/fast-serialization)
  - [jackson](http://wiki.fasterxml.com/JacksonHome)
  - [Gson](https://github.com/google/gson)
  - [fastjson](https://github.com/alibaba/fastjson)
  - [msgpack](https://msgpack.org/)
  - [avro](https://avro.apache.org/)
  - [XStream](http://x-stream.github.io/)
  - [几种 Java 序列化方案的性能比较](https://github.com/eishay/jvm-serializers/wiki)
  
* 本地缓存
  - [Google Guava](https://github.com/google/guava) 推荐指数: ★★★★★
  - [Caffeine](https://github.com/ben-manes/caffeine)

* 分布式缓存
  - [Jedis](https://github.com/xetorthio/jedis) 推荐指数: ★★★★★
  - [Redisson](https://github.com/redisson/redisson) 推荐指数: ★★★★★
  - [Ehcache](http://www.ehcache.org/)
  - [Hazelcast](https://hazelcast.com/)

* 任务调度框架
  - [Quartz](http://www.quartz-scheduler.org/)

* 字节码操作
  - [Javassist](http://jboss-javassist.github.io/javassist/)
  - [cglib](https://github.com/cglib/cglib)

* Netflix OSS
  - [Eureka](https://github.com/Netflix/eureka)
  - [网关服务 Zuul 2](https://github.com/Netflix/zuul)
  - [Ribbon](https://github.com/Netflix/ribbon)
  - [容错 Hystrix](https://github.com/Netflix/Hystrix/)
  - [分布式配置管理 Archaius](https://github.com/Netflix/archaius)
  - [Chaos Monkey](https://github.com/Netflix/chaosmonkey)

* Zookeeper客户端库
  - [Apache Curator](http://curator.apache.org/)
  - [zkclient](https://github.com/sgroschupf/zkclient)

* NIO框架
  - [Netty](http://netty.io/)
  - [Grizzly]()
  - [Vert.x](https://vertx.io/)

* Bean 属性拷贝
  - [Dozer](http://dozer.sourceforge.net/)
  - [commons-beanutils](http://commons.apache.org/proper/commons-beanutils/)

* Web 容器
  - [Tomcat](http://tomcat.apache.org/)
  - [Jetty](http://www.eclipse.org/jetty/)
  - [Undertow](http://undertow.io/)

* 工具类
  - [Lomobok](https://www.projectlombok.org/) 推荐指数: ★★★★★
  - [commons-codec](http://commons.apache.org/proper/commons-codec/)
  - [commons-lang3](https://commons.apache.org/proper/commons-lang/)

* 模版引擎
  - [Apache Velocity](http://velocity.apache.org/)
  - [新一代Java模板引擎Thymeleaf](https://www.thymeleaf.org/)

* 日志
  - [slf4j](https://www.slf4j.org/)
  - [logback](https://logback.qos.ch/)
  - [log4j2](https://logging.apache.org/log4j/2.x/)

* 单元测试
  - [JUnit 4](https://junit.org/junit4/)
  - [Mockito](http://site.mockito.org/)

* 依赖管理\&构建工具
  - [Maven](https://maven.apache.org/)
  - [Gradle](https://gradle.org/)

* 版本控制
  - [Git](https://git-scm.com/)
  - [SVN]()
  - [Mercurial](https://www.mercurial-scm.org/)
  
## 中间件
* RPC框架
  - [阿里巴巴 dubbo](http://dubbo.io/)
  - [新浪微博 motan](https://github.com/weibocom/motan)
  - [Google gRPC](https://www.grpc.io/)
  - [蚂蚁金服 sofa-rpc](https://github.com/alipay/sofa-rpc)
  - [百度 brpc](https://github.com/brpc/brpc)
  - [腾讯 Tars](https://github.com/Tencent/Tars)
  - [大众点评 pigeon](https://github.com/dianping/pigeon)

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
  - [大众点评 zebra](https://github.com/dianping/zebra)
  - [mango](http://mango.jfaster.org/)

* 配置中心
  - [百度 disconf](https://github.com/knightliao/disconf)
  - [携程 apollo](https://github.com/ctripcorp/apollo)

* 分布式任务调度
  - [Elastic-Job](http://elasticjob.io/)
  - [TBSchedule](http://code.taobao.org/p/tbschedule/wiki/tbschedule-quick-start/)
  - [xxl-job](https://github.com/xuxueli/xxl-job)

* 分布式ID生成器
  - [Twitter Snowflake](https://github.com/twitter/snowflake)
  - [百度 uid-generator](https://github.com/baidu/uid-generator)
  - [美团 Leaf](https://tech.meituan.com/MT_Leaf.html)

* TCC分布式事务框架
  - [tcc-transaction](https://github.com/changmingxie/tcc-transaction)
  - [ByteTCC](https://github.com/liuyangming/ByteTCC)
  - [Hmily](https://github.com/yu199195/hmily)
  
* APM
  - [大众点评 Cat](https://github.com/dianping/cat)
  - [Pinpoint](https://github.com/naver/pinpoint)
  - [Open-Falcon](http://open-falcon.org/)
  
* 分布式链路追踪
  - [Zipkin](https://zipkin.io/)
  - [Jaeger](https://www.jaegertracing.io/)
  - [OpenTracing](http://opentracing.io/)
  - [大众点评 Cat](https://github.com/dianping/cat)
  - [Apache SkyWalking](https://github.com/apache/incubator-skywalking)

* 分布式文件系统
  - [FastDFS](https://github.com/happyfish100/fastdfs)

* 数据库binlog解析
  - [阿里巴巴 canal](https://github.com/alibaba/canal)
  - [大众点评 puma](https://github.com/dianping/puma)

## RDBMS

### MySQL
* MySQL 索引

### PostgreSQL
* PG

## NoSQL
NoSQL(NoSQL = Not Only SQL)

* [Redis](https://redis.io/)
* [MongoDB](https://www.mongodb.com/)
* [HBase](http://hbase.apache.org/)
* [Elasticsearch](https://www.elastic.co/products/elasticsearch)

## 分布式
数据一致性、服务治理、服务降级

## 分布式事务
2PC、3PC、CAP、BASE、 可靠消息最终一致性、最大努力通知、TCC

## 微服务
SOA、康威定律

Spring Boot
Spring Cloud
Docker & Kubernets
ServiceMesh

* 服务注册\&发现
  - [Zookeeper](https://zookeeper.apache.org/)
  - [Consul](https://www.consul.io/)
  - [etcd](https://coreos.com/etcd/)

* 分布式协调\&选主
  - [Apache Zookeeper](https://zookeeper.apache.org/)

* 应用监控
  - [Prometheus](https://prometheus.io/)
  - [Graphite](http://graphiteapp.org/)
  - [Ganglia](http://ganglia.info/)
  - [Zabbix](https://www.zabbix.com/)
  - [Grafana](https://grafana.com/)
  
## 安全
* [SQL注入]()

## 团队管理
* [面试流程]()

## 线上问题排查
* [Java进程CPU使用率高排查](https://github.com/oldratlee/useful-scripts/blob/master/docs/java.md#beer-show-busy-java-threads)
* [Java OOM问题排查]()
* [BTrace 使用]()

## 架构设计
* [后端架构师技术图谱](https://github.com/xingshaocheng/architect-awesome)

## 互联网公司架构
* [互联网公司技术架构](https://github.com/davideuler/architecture.of.internet-product)
* [互联网公司架构: 淘宝技术架构，阿里巴巴技术架构](https://github.com/davideuler/architecture.taobao-alibaba)
* [互联网公司架构: 微信技术架构， 腾讯技术架构](https://github.com/davideuler/architecture.wechat-tencent)
* [互联网公司架构: 美团点评技术架构](https://github.com/davideuler/architecture.meituan-dianping)



