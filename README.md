# Github收藏夹  

### 这是个收藏夹, 收集了Github上看到的各种不同的优秀工具,框架,知识合集  
- [Web框架](#Web框架)
- [RPC](#RPC)
- [分布式](#分布式)
- [微服务](#微服务)
- [通用框架](#通用框架)
- [持续集成&交付](#持续集成&交付)
- [数据库](#数据库)
- [缓存](#缓存)
- [流&消息](#流&消息)
- [应用定义&镜像构建](#应用定义&镜像构建)
- [搜索引擎](#搜索引擎)
- [调度&编排](调度&编排)
- [服务协调&发现](#服务协调&发现)
- [服务代理](#服务代理)
- [API网关](#API网关)
- [ServiceMesh](#ServiceMesh)
- [云原生存储](#云原生存储)
- [容器](#容器)
- [云原生网络](#云原生网络)
- [自动化&配置](#自动化&配置)
- [安全&合规](#安全&合规)
- [监控](#监控)
- [日志](#日志)
- [测试](#测试)
- [混沌工程](#混沌工程)
- [插件&工具](#插件&工具)
- [相关教程](#相关教程)
- [文档汉化](#文档汉化)
- [面试相关](#面试相关)
- [其他资源](#其他资源)
- [优秀blog](#优秀blog)

- - -
## Web框架
* [jfinal](https://github.com/jfinal/jfinal) -  Java 语言的极速 WEB + ORM 框架, 其核心设计目标是开发迅速、代码量少、学习简单、功能强大、轻量级、易扩展、Restful.

## RPC
* [dubbo](https://github.com/alibaba/dubbo) - 阿里出品的使用范围广泛的RPC框架
* [motan](https://github.com/weibocom/motan) - 微博出品的跨语言的RPC框架
* [brpc](https://github.com/brpc/brpc) - 百度出品的工业级RPC框架
* [grpc](https://github.com/grpc/grpc) - gRPC是一个领先的, 开源的, 高性能的RPC框架, 可以在任何地方运行. gRPC使客户端和服务端的通信变得透明, 并乐意简化连接的创建
* [Tars](https://github.com/Tencent/Tars) - 腾讯出品的高性能RPC框架
* [sofa-rpc](https://github.com/alipay/sofa-rpc) - 蚂蚁金服出品的高可扩展性、高性能、生产级的 Java RPC 框架

## 分布式
* [zookeeper](https://github.com/apache/zookeeper) apache旗下的分布式服务协调框架
* [etcd](https://github.com/etcd-io/etcd) 一个可依赖的分布式key-value存储系统, 用于分布式环境下保存关键数据

## 微服务
* [fabric8](https://github.com/fabric8io/fabric8) - 基于Docker, Kubernetes and Jenkins的微服务平台

## 通用框架
* [guava](https://github.com/google/guava) - google出品的非常好用的Java工具包
* [netty](https://github.com/netty/netty) - 事件驱动的支持异步的网络框架
* [hystrix](https://github.com/Netflix/Hystrix) - Netflix出品的熔断器
* [uid-generator](https://github.com/baidu/uid-generator) - 百度出品的基于snowflake的唯一Id生成器
* [fastjson](https://github.com/alibaba/fastjson) - 阿里出品的解析/生成JSON的java框架
* [swagger](https://github.com/swagger-api/swagger-ui) - java API管理工具
* [protobuf](https://github.com/google/protobuf) - google出品的平台无关,语言无关的序列化工具
* [cqengine](https://github.com/npgall/cqengine) - 可以在Java的collection中进行SQL-like查询的工具
* [jetcache](https://github.com/alibaba/jetcache) - 阿里出品的Java缓存框架, "用起来比Spring Cache更方便"
* [vert.x](https://github.com/eclipse/vert.x) - JVM上用于开发reactive程序的工具包

## 持续集成&交付
* [skaffold](https://github.com/GoogleContainerTools/skaffo) - Google出品的一款命令行工具, 用于促进Kubernetes应用程序的持续开发
* [travis](https://github.com/travis-ci/travis-ci) - 针对github上项目的免费的持续集成平台

## 数据库
* [sharding-jdbc](https://github.com/shardingjdbc/sharding-jdbc) - 开源的分布式数据库中间件解决方案。它在Java的JDBC层以对业务应用零侵入的方式额外提供数据分片, 读写分离, 柔性事务和分布式治理能力。并在其基础上提供封装了MySQL协议的服务端版本, 用于完成对异构语言的支持.
* [h2database](https://github.com/h2database/h2database) - 快速的,开源的,支持JDBC API的内存数据库
* [mapper](https://github.com/abel533/Mapper) - MyBatis 通用 Mapper
* [tcc-transaction](https://github.com/changmingxie/tcc-transaction) - TCC型事务java实现
* [mycat](https://github.com/MyCATApache/Mycat-Server) - 基于阿里cobar改良的分布式数据库中间件, 官宣为一个模拟为MySQL Server的超级数据库
* [cobar](https://github.com/alibaba/cobar) - 阿里出品的支持sharding的proxy(很久没有维护了)
* [ignite](https://github.com/apache/ignite) - Apache旗下的一款以内存为中心,多模型的,分布式数据库/cache.号称可以以内存级别的速度处理Pb级别的数据.
* [vitess](https://github.com/vitessio/vitess) - Vitess是一个用于MySQL水平扩展的数据库集群系统
* [arangodb](https://github.com/arangodb/arangodb) - ArangoDB是一个原生的多模型数据库, 具有文档, 图形和键值的灵活数据模型。使用方便的类SQL查询语言或JavaScript扩展构建高性能应用程序。
* [druid](https://github.com/alibaba/druid) - 阿里出品的号称"为监控而生"的数据库连接池

## 缓存
* [redis](https://github.com/antirez/redis) - 可以当成数据库, 缓存, 消息队列使用的内存数据结构存储工具.
* [ehcache](https://github.com/ehcache/ehcache3) - 号称使用最为广泛的java缓存

## 流&消息
* [kafka](https://github.com/apache/kafka) - 隶属于Apache的分布式流平台
* [rocketmq](https://github.com/apache/rocketmq) - 隶属于Apache的分布式消息跟流平台, 低延迟, 高性能, 高可靠, 万亿级别容量, 动态扩展. 
* [activemq](https://github.com/apache/activemq) - 隶属于Apache的高性能消息队列
* [nats server](https://github.com/nats-io/gnatsd) - NATS Server是一个简单, 高性能的开源消息系统, 适用于云原生应用程序, 物联网消息传递和微服务架构。
* [heron](https://github.com/apache/incubator-heron) - Apache Heron(孵化中)是一款来自Twitter的实时, 分布式, 具有容错性的流处理引擎
* [nifi](https://github.com/apache/nifi) - Apache NiFi是一个易于使用, 功能强大且可靠的系统, 用于处理和分发数据。

## 应用定义&镜像构建
* [helm](https://github.com/helm/helm) - 一个Kubernetes包管理器

## 搜索引擎
* [elasticsearch](https://github.com/elastic/elasticsearch) - 支持分布式的Restful的搜索引擎

## 调度&编排
* [kubernetes](https://github.com/kubernetes/kubernetes) - Kubernetes是一个开源系统, 用于管理多个主机上的容器化应用程序;提供应用程序部署, 维护和扩展的基本机制。
* [elastic-job](https://github.com/elasticjob/elastic-job-lite) - Elastic-Job是一个分布式调度解决方案, 由两个相互独立的子项目Elastic-Job-Lite和Elastic-Job-Cloud组成.
* [flink](https://github.com/apache/flink) - 隶属于Apache的流处理框架,拥有强大的流处理以及批量处理的能力.
* [quartz](https://github.com/quartz-scheduler/quartz) - 功能丰富的,几乎可以与任何java程序集成的调度框架
* [xxl-job](https://github.com/xuxueli/xxl-job) - 分布式任务调度平台XXL-JOB

## 服务协调&发现
* [coredns](https://github.com/coredns/coredns) - CoreDNS(Go语言编写)是一个链接插件的DNS服务器, 每个插件都执行DNS功能。

## 服务代理
* [envoy](https://github.com/envoyproxy/envoy) - Envoy是一个开源服务代理, 专为云应用而设计

## API网关
* [3scale](https://github.com/3scale/apicast) - APIcast是一个建立在NGINX之上的API网关. 它是Red Hat 3scale API管理平台的一部分

## ServiceMesh
* [linkerd](https://github.com/linkerd/linkerd) - Linkerd旨在透明地向所有服务间通信添加服务发现, 负载平衡, 故障处理, 检测和路由, 使应用程序变得安全可靠.

## 云原生存储
* [rook](https://github.com/rook/rook) - Rook是Kubernetes的开源云本地存储协调器，为各种存储解决方案提供平台，框架和支持，以便与云原生环境本地集成.

## 容器
* [containerd](https://github.com/containerd/containerd) - 一个开放且可靠的容器运行时

## 云原生网络
* [cni](https://github.com/containernetworking/cni) - Container Network Interface - 用于Linux容器的网络体系

## 自动化&配置
* [ansible](https://github.com/ansible/ansible) - IT自动化的平台, 使系统跟程序更加容易部署
* [disconf](https://github.com/knightliao/disconf) - 分布式配置管理平台
* [mgmt](https://github.com/purpleidea/mgmt) - 号称下一代的配置管理平台
* [QConf](https://github.com/Qihoo360/QConf) - 奇虎的分布式配置管理平台
* [apollo](https://github.com/ctripcorp/apollo) - 携程框架部门研发的分布式配置中心, 能够集中化管理应用不同环境、不同集群的配置, 配置修改后能够实时推送到应用端, 并且具备规范的权限、流程治理等特性, 适用于微服务配置管理场景.

## 安全&合规
* [Shiro](https://github.com/apache/shiro) - 隶属于apache的功能强大的java安全框架
* [knox](https://github.com/pinterest/knox) - know用于管理其他服务中使用到的秘钥相关信息

## 监控
* [prometheus](https://github.com/prometheus/prometheus) - CNCF项目, 用于监控其他系统或服务. 它以给定的时间间隔从目标收集指标，根据规则进行评估，显示结果，如果达到某些监控条件, 还可以触发警报.

## 日志
* [log4j](https://github.com/apache/log4j) - apache旗下的老牌日志工具

## 测试
* [selenium](https://github.com/SeleniumHQ/selenium) - 自动化浏览器测试框架

## 混沌工程
* [chaostoolkit](https://github.com/chaostoolkit/chaostoolkit) - 为社区所需的各种形式的混沌工程工具提供免费，开放和社区驱动的工具包和API。

## 插件&工具
* [fast-syntax-highlighting](https://github.com/zdharma/fast-syntax-highlighting) - zsh的语法高亮插件
* [nosqlclient](https://github.com/nosqlclient/nosqlclient) - mongodb的客户端
* [mybatis-generator-gui](https://github.com/zouzg/mybatis-generator-gui) mybatis generator的GUI工具
* [git_commit_template](https://github.com/joelparkerhenderson/git_commit_template) - 一个git message的模板
* [gitignore.io](https://github.com/joeblau/gitignore.io) - 可以方便的自定义.gitignore文件
* [shadowsocks](https://github.com/shadowsocks) - 这个无需介绍了,懂的自然都懂.
* [source-code-pro](https://github.com/adobe-fonts/source-code-pro) - Adobe开源的编程字体

## 相关教程
* [Knowledge Graph](https://github.com/gocn/knowledge) - Go社区的知识图谱
* [bash-guide](https://github.com/Idnan/bash-guide) - Bash相关命令教程
* [p3c](https://github.com/alibaba/p3c) - 阿里巴巴Java代码规范
* [JCFInternals](https://github.com/CarpenterLee/JCFInternals) - Java collection讲解
* [elasticsearch-definitive-guide](https://github.com/elastic/elasticsearch-definitive-guide) - 汉化elasticsearch权威指南
* [zju-icicles](https://github.com/QSCTech/zju-icicles) - 浙江大学课程攻略共享计划
* [deep-learning](https://github.com/Robinwho/Deep-Learning) - 深度学习/人工智能/机器学习资料汇总
* [pythontutorial3](https://github.com/sixu05202004/pythontutorial3) - python 3.5.1 tutorial中文版
* [liaoxuefeng](https://www.liaoxuefeng.com/) - 廖雪峰的git,python,javascript教程
* [git-tutorial](https://backlog.com/git-tutorial/cn/) - 号称是猴子都能看懂的git教程
* [java8-tutorial](https://github.com/winterbe/java8-tutorial) - java 8教程
* [Linux-Tutorial](https://github.com/judasn/Linux-Tutorial) - java程序员眼中的linux
* [free-programming-books](https://github.com/justjavac/free-programming-books-zh_CN) - 免费的计算机编程类中文书籍
* [docker-handbook](https://github.com/rootsongjc/docker-handbook) - 宋净超同学出品的docker handbook
* [kubernetes-handbook](https://github.com/rootsongjc/kubernetes-handbook) - 宋净超同学出品的kubernetes中文指南
* [kubernetes-handbook](https://github.com/feiskyer/kubernetes-handbook) - feiskyer出品的Kubernetes指南
* [cni](https://github.com/CloudNativeInfra/cni) - The book Cloud Native Infrastructure
* [spring-boot-examples](https://github.com/souyunku/spring-boot-examples) - Spring Boot 学习教程
* [How-To-Ask-Questions-The-Smart-Way](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way) - 提问的智慧
* [SpringCloudBook](https://github.com/dyc87112/SpringCloudBook) - Spring Cloud微服务实战
* [java-design-patterns](https://github.com/iluwatar/java-design-patterns) - Java实现的各种设计模式
* [architecture.wechat-tencent](https://github.com/davideuler/architecture.wechat-tencent) - 互联网公司架构: 微信技术架构,  腾讯技术架构
* [gopl-zh](https://github.com/golang-china/gopl-zh) - Go语言圣经中文版
* [prometheus_practice](https://github.com/songjiayang/prometheus_practice) - 包括 Prometheus 安装, 基础监控, 常用 exporter, 性能优化和大量实战经验

## 文档汉化
* [kafka-doc-zh](https://github.com/apachecn/kafka-doc-zh/) - Kafka 中文文档
* [redis](https://github.com/huangz1990/redis) - Redis Command Reference全文的中文翻译版
* [spring-5-framework-doc](https://github.com/lfvepclr/spring-5-framework-doc) - Spring 5文档翻译
* [java-nio-zh](https://github.com/avenwu/java-nio-zh) - 汉化的Java NIO教程
* [istio中文文档](https://github.com/doczhcn/istio) - Istio官方文档中文版
* [build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang) - 包含多语言(包含中文)版本的GO教程

## 面试相关
* [Back-End-Developer-Interview-Questions](https://github.com/arialdomartini/Back-End-Developer-Interview-Questions) - 后端开发面试题
* [The-Art-Of-Programming-By-July](https://github.com/julycoding/The-Art-Of-Programming-By-July) - July的<<编程之法：面试和算法心得>>
* [hunter](https://github.com/lietoumai/Hunter) - 面试技巧相关
* [interview-notebook](https://github.com/CyC2018/Interview-Notebook) - 技术面试需要掌握的基础知识
* [interviews](https://github.com/kdn251/interviews) - 找工作需要了解的基础技术
* [2018-Java-Interview](https://github.com/xbox1994/2018-Java-Interview) - 2018年几个大厂的面试宝典

## 其他资源
* [awesome-java](https://github.com/akullpp/awesome-java) - 整理了相当多java生态圈的相关资源
* [awesome-scalability](https://github.com/binhnguyennus/awesome-scalability) - 整理了相当多的高扩展,高可用,高性能等的设计模式
* [awesome-blockchain-cn](https://github.com/chaozh/awesome-blockchain-cn) - 收集所有区块链(BlockChain)技术开发相关资料, 包括Fabric和Ethereum开发资料
* [cloud-native-slides-share](https://github.com/rootsongjc/cloud-native-slides-share) - 收集了大量的cloud native相关的大会资料,开源书籍以及类似信息
* [IntelliJ-IDEA-Tutorial](https://github.com/judasn/IntelliJ-IDEA-Tutorial) - IDEA教程
* [skill-map](https://github.com/TeamStuQ/skill-map) - 程序员技能图谱
* [tenant-point](https://github.com/soulteary/tenant-point) - 租房要点, 适用于北上广深杭
* [English-level-up-tips-for-Chinese](https://github.com/byoungd/English-level-up-tips-for-Chinese) - 高效学习英语

## 优秀blog
* [TiDB博客](https://pingcap.com/blog-cn/) - TiDB官网的博客
* [阿里中间件](http://jm.taobao.org/) - 阿里中间件团队博客
* [Tim Yang](https://timyang.net/) - 后端技术 by Tim Yang
* [许令波](https://github.com/xulingbo/xulingbo.github.io/issues/) - 许令波的Issue
* [martinfowler](https://martinfowler.com/) - martin fowler的博客
* [美团点评技术团队](https://tech.meituan.com/) - 美团点评技术团队的博客
* [CoolShell](https://coolshell.cn/) - 左耳朵耗子的酷壳
* [并发编程网](http://ifeve.com/concurrency-site/) - 并发编程网
* [今日头条技术博客](https://techblog.toutiao.com/) - 今日头条技术博客
* [developerworks](https://www.ibm.com/developerworks/cn/) - IBM developerworks
* [伪架构师](https://blog.fleeto.us/) - 崔秀龙的博客