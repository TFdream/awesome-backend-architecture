# awesome-backend-architecture
涵盖后端java知识、常用技术框架、数据库、开源中间件、微服务、系统架构、线上问题定位/处理、团队管理、一线互联网公司架构案例等。

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
  - [Spring Framework](https://spring.io/projects/spring-framework)
  - [Spring Boot](https://spring.io/projects/spring-boot)
  - [Spring Cloud](https://spring.io/projects/spring-cloud)

* Web框架
  - [Spring Web MVC](https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html)
  - [Spring WebFlux](https://docs.spring.io/spring/docs/5.0.0.BUILD-SNAPSHOT/spring-framework-reference/html/web-reactive.html)
  - [Struts 2](https://struts.apache.org/)
  - [paoding-rose](http://www.54chen.com/rose.html)
  - [Blade](https://github.com/lets-blade/blade)
  - [JFinal](https://github.com/jfinal/jfinal)
  
* ORM 框架
  - [MyBatis](http://www.mybatis.org/mybatis-3/)
  - [Hibernate](http://hibernate.org/) 
  - [Spring JDBC](https://spring.io/projects/spring-framework)
  - [Spring Data JPA](https://projects.spring.io/spring-data-jpa/)
  - [jOOQ](https://www.jooq.org/)
  - [DbUtils](https://commons.apache.org/proper/commons-dbutils/)

* Http 网络请求
  - [OkHttp](http://square.github.io/okhttp/)【强烈推荐】
  - [AsyncHttpClient](https://github.com/AsyncHttpClient/async-http-client)
  - [Apache HttpClient](http://hc.apache.org/httpcomponents-client-4.5.x/) 【不推荐】

* JSON library
  - [jackson](http://wiki.fasterxml.com/JacksonHome)
  - [Google Gson](https://github.com/google/gson)
  - [Alibaba fastjson](https://github.com/alibaba/fastjson)【近期安全漏洞比较多】
  - [Square Moshi](https://github.com/square/moshi)

* 数据库连接池
  - [Alibaba druid](https://github.com/alibaba/druid) 【强烈推荐】
  - [HikariCP](http://brettwooldridge.github.io/HikariCP/) 【强烈推荐，Spring Boot 2.x默认数据源】
  - [Tomcat JNDI Datasource](http://tomcat.apache.org/tomcat-8.5-doc/jndi-datasource-examples-howto.html) 
  - [c3p0](https://www.mchange.com/projects/c3p0/)【不推荐】
  - [DBCP](http://commons.apache.org/proper/commons-dbcp/)【不推荐】

* 日期\&时间处理
  - [Joda-Time](http://www.joda.org/joda-time/)
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
  - [Google Guava](https://github.com/google/guava) 
  - [Caffeine](https://github.com/ben-manes/caffeine)

* 分布式缓存
  - [Jedis](https://github.com/xetorthio/jedis) 
  - [Redisson](https://github.com/redisson/redisson) 
  - [Ehcache](http://www.ehcache.org/)
  - [Hazelcast](https://hazelcast.com/)

* 缓存框架
  - [阿里巴巴 jetcache](https://github.com/alibaba/jetcache) 
  - [Spring Cache](https://docs.spring.io/spring/docs/3.2.x/spring-framework-reference/html/cache.html)

* 任务调度框架
  - [Quartz](http://www.quartz-scheduler.org/)
  
* 字节码操作
  - [Javassist](http://jboss-javassist.github.io/javassist/)
  - [cglib](https://github.com/cglib/cglib)
  - [Square JavaPoet](https://github.com/square/javapoet)
  - [asm](https://asm.ow2.io/)
  
* Netflix OSS
  - [Eureka](https://github.com/Netflix/eureka)
  - [Zuul](https://github.com/Netflix/zuul)
  - [Ribbon](https://github.com/Netflix/ribbon)
  - [Feign](https://github.com/Netflix/feign)
  - [Hystrix](https://github.com/Netflix/Hystrix/)
  - [Archaius](https://github.com/Netflix/archaius)
  - [Chaos Monkey](https://github.com/Netflix/chaosmonkey)

* Zookeeper客户端库
  - [Apache Curator](http://curator.apache.org/)
  - [zkclient](https://github.com/sgroschupf/zkclient)

* NIO框架
  - [Netty](http://netty.io/)【强烈推荐】
  - [Apache MINA](https://mina.apache.org/)

* Bean 属性拷贝
  - [Dozer](http://dozer.sourceforge.net/)
  - [commons-beanutils](http://commons.apache.org/proper/commons-beanutils/)

* Web 容器
  - [Tomcat](http://tomcat.apache.org/)
  - [Jetty](http://www.eclipse.org/jetty/)
  - [Undertow](http://undertow.io/)

* 工具类
  - [Lomobok](https://www.projectlombok.org/) 【强烈推荐】
  - [Apache commons-codec](http://commons.apache.org/proper/commons-codec/)
  - [Apache commons-lang3](https://commons.apache.org/proper/commons-lang/)
  - [Apache commons-fileupload](http://commons.apache.org/proper/commons-fileupload/)
  - [Apache commons-email](http://commons.apache.org/proper/commons-email/)
  
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
  - [Apache dubbo](http://dubbo.incubator.apache.org/)
  - [新浪微博 motan](https://github.com/weibocom/motan)
  - [蚂蚁金服 sofa-rpc](https://github.com/alipay/sofa-rpc)
  - [Google gRPC](https://www.grpc.io/)
  - [百度 brpc](https://github.com/brpc/brpc)
  - [腾讯 Tars](https://github.com/Tencent/Tars)
  - [大众点评 pigeon](https://github.com/dianping/pigeon)

* MQ消息
  - [RabbitMQ](http://www.rabbitmq.com/)
  - [Apache Kafka](http://kafka.apache.org/)
  - [Apache RocketMQ](https://rocketmq.apache.org/)
  - [Apache ActiveMQ](http://activemq.apache.org/)

* 数据库Sharding
  - [Apache ShardingSphere](https://github.com/apache/incubator-shardingsphere)
  - [阿里巴巴 Cobar](https://github.com/alibaba/cobar)
  - [淘宝 tddl](https://github.com/alibaba/tb_tddl)
  - [Mycat 数据库分库分表中间件](http://www.mycat.io/)
  - [大众点评 zebra](https://github.com/dianping/zebra)
  - [mango](http://mango.jfaster.org/)

* 服务注册&发现
  - [Zookeeper](https://zookeeper.apache.org/)
  - [阿里巴巴 Nacos](https://nacos.io/zh-cn/index.html)
  - [Netflix Eureka](https://github.com/Netflix/eureka)【停止更新】
  - [Consul](https://www.consul.io/)
  
* 配置中心
  - [携程 apollo](https://github.com/ctripcorp/apollo) 【强烈推荐】
  - [百度 disconf](https://github.com/knightliao/disconf)
  - [阿里巴巴 Nacos](https://nacos.io/zh-cn/index.html)
  
* 流量控制 & 熔断降级
  - [Hystrix](https://github.com/Netflix/Hystrix)【停止更新】
  - [resilience4j](https://github.com/resilience4j/resilience4j)【Spring官方推荐】
  - [阿里巴巴 Sentinel](https://github.com/alibaba/Sentinel)
  - [三者功能特性对比](https://github.com/alibaba/Sentinel/wiki/Guideline:-%E4%BB%8E-Hystrix-%E8%BF%81%E7%A7%BB%E5%88%B0-Sentinel)
  
* 分布式任务调度
  - [Elastic-Job](https://github.com/apache/shardingsphere-elastic-job-lite)【已经捐给Apache了，由shardingsphere团队维护】
  - [xxl-job](https://github.com/xuxueli/xxl-job)
  - [TBSchedule](http://code.taobao.org/p/tbschedule/wiki/tbschedule-quick-start/)

* 分布式ID生成器
  - [Twitter Snowflake](https://github.com/twitter/snowflake)
  - [百度 uid-generator](https://github.com/baidu/uid-generator)
  - [美团点评 Leaf](https://github.com/Meituan-Dianping/Leaf)

* 分布式事务框架
  - [阿里巴巴 Seata](https://github.com/seata/seata)
  - [tcc-transaction](https://github.com/changmingxie/tcc-transaction)
  - [ByteTCC](https://github.com/liuyangming/ByteTCC)
  - [Hmily](https://github.com/yu199195/hmily)
  - [tx-lcn](https://github.com/codingapi/tx-lcn)
    
* APM
  - [大众点评 Cat](https://github.com/dianping/cat)
  - [Apache SkyWalking](https://github.com/apache/incubator-skywalking)
  - [Pinpoint](https://github.com/naver/pinpoint)
  - [Open-Falcon](http://open-falcon.org/)
  
* 分布式链路追踪
  - [Zipkin](https://zipkin.io/)
  - [Jaeger](https://www.jaegertracing.io/)
  - [OpenTracing](http://opentracing.io/)
  - [大众点评 Cat](https://github.com/dianping/cat)

* 分布式文件系统
  - [FastDFS](https://github.com/happyfish100/fastdfs)
  - [Ceph](https://ceph.io/)
  
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



