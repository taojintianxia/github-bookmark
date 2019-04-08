# Github收藏夹  

### 这是个收藏夹, 收集了Github上看到的各种不同的优秀工具,框架,知识合集  
- [RPC](#RPC)
- [微服务](#微服务)
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
- [游戏](#游戏)

- - -
## RPC
* [dubbo](https://github.com/alibaba/dubbo) - 阿里出品的使用范围广泛的RPC框架
* [motan](https://github.com/weibocom/motan) - 微博出品的跨语言的RPC框架
* [brpc](https://github.com/brpc/brpc) - 百度出品的工业级RPC框架
* [grpc](https://github.com/grpc/grpc) - gRPC是一个领先的, 开源的, 高性能的RPC框架, 可以在任何地方运行. gRPC使客户端和服务端的通信变得透明, 并乐意简化连接的创建
* [Tars](https://github.com/Tencent/Tars) - 腾讯出品的高性能RPC框架
* [sofa-rpc](https://github.com/alipay/sofa-rpc) - 蚂蚁金服出品的高可扩展性、高性能、生产级的 Java RPC 框架

## 微服务
* [fabric8](https://github.com/fabric8io/fabric8) - 基于Docker, Kubernetes and Jenkins的微服务平台

## 持续集成&交付
* [skaffold](https://github.com/GoogleContainerTools/skaffold) - Google出品的一款命令行工具, 用于促进Kubernetes应用程序的持续开发
* [travis](https://github.com/travis-ci/travis-ci) - 针对github上项目的免费的持续集成平台
* [Argo](https://github.com/argoproj/argo) - 用于Kubernetes的容器原生的工作流引擎
* [Brigade](https://github.com/azure/brigade) - 基于事件的Kubernetes脚本
* [Buildkite](https://github.com/buildkite/agent) - Buildkite Agent是一个用Golang编写的开源工具包，用于在任何设备或网络上安全地运行构建作业
* [Concourse](https://github.com/concourse/concourse) - Concourse是一个用Go编写的自动化系统. 它最常用于CI / CD，可以扩展到任何类型的从简单到复杂自动化pipline
* [ContainerOps](https://github.com/Huawei/containerops) - Devops编排工具
* [Drone](https://github.com/drone/drone) - Drone是一个用Go写的基于Docker的持续交付平台
* [Gitkube](https://github.com/hasura/gitkube) - Gitkube是一个使用git push在Kubernetes上构建和部署Docker镜像的工具
* [GitLab](https://github.com/gitlabhq/gitlabhq) - Gitlab, 第一款实现了完整的Devops生命周期的应用
* [GoCD](https://github.com/gocd/gocd) - 持续交付的server, GoCD可帮助您自动化和简化构建测试 - 发布周期，从而无忧无虑地持续交付产品
* [Habitus](https://github.com/cloud66-oss/habitus) - Habitus为Docker构建添加了工作流, 这意味着您可以基于工作流创建一系列构建，并生成最终的Docker镜像
* [Jenkins](https://github.com/jenkinsci/jenkins) - 最流行的CI/CD工具, 提供多达上千种插件支持, 几乎支持任何自动化构建
* [JenkinsX](https://github.com/jenkins-x/jx) - Jenkins X使用Jenkins，Knative Build，Prow，Skaffold和Helm为Kubernetes提供自动CI + CD，并提供Pull Request的预览环境
* [Spinnaker](https://github.com/spinnaker/spinnaker) - Spinnaker是一个开源的，Multi-Cloud的持续交付平台，以快速且高可用的方式发布软件
* [Flux](https://github.com/weaveworks/flux) - 当在Continuous Delivery管道末端用作部署工具时，Flux最有用. Flux将确保您的新容器映像和配置更改传播到集群
* [Wercker](https://github.com/wercker/wercker) - wercker是为wercker.com提供所有构建和部署作业的命令行工具，它在Docker的帮助下在本地计算机上运行
* [Zuul CI](https://github.com/openstack-infra/zuul) - Zuul是一个推动持续集成，交付和部署系统的计划，重点关注project gating和相互关联的项目, 此项目非Netflix的zuul

## 数据库
* [sharding-sphere](https://github.com/sharding-sphere/sharding-sphere) - 开源的分布式数据库中间件解决方案。它在Java的JDBC层以对业务应用零侵入的方式额外提供数据分片, 读写分离, 柔性事务和分布式治理能力。并在其基础上提供封装了MySQL协议的服务端版本, 用于完成对异构语言的支持
* [HikariCP](https://github.com/brettwooldridge/HikariCP) - 可靠的高性能JDBC连接池, 号称"zero-overhead"生产就绪, 仅仅130Kb
* [h2database](https://github.com/h2database/h2database) - 快速的,开源的,支持JDBC API的内存数据库
* [mycat](https://github.com/MyCATApache/Mycat-Server) - 基于阿里cobar改良的分布式数据库中间件, 官宣为一个模拟MySQL Server的超级数据库
* [cobar](https://github.com/alibaba/cobar) - 阿里出品的支持sharding的proxy(很久没有维护了)
* [ignite](https://github.com/apache/ignite) - Apache旗下的一款以内存为中心,多模型的分布式数据库/cache.号称可以以内存级别的速度处理Pb级别的数据.
* [vitess](https://github.com/vitessio/vitess) - Vitess是一个用于MySQL水平扩展的数据库集群系统
* [arangodb](https://github.com/arangodb/arangodb) - ArangoDB是一个原生的多模型数据库, 具有文档, 图形和键值的灵活数据模型。使用方便的类SQL查询语言或JavaScript扩展构建高性能应用程序
* [bigchaindb](https://github.com/bigchaindb/bigchaindb) - BigchainDB是区块链数据库
* [CarbonData](https://github.com/apache/carbondata) - Apache CarbonData是一种索引的柱状数据存储解决方案，用于在大数据平台上进行快速分析，例如Apache Hadoop，Apache Spark等
* [Cassandra](https://github.com/apache/cassandra) - Apache Cassandra是一套开源分布式NoSQL数据库系统。它最初由Facebook开发，用于储存收件箱等简单格式数据，集Google BigTable的数据模型与Amazon Dynamo的完全分布式的架构于一身。Facebook于2008将 Cassandra 开源，此后，由于Cassandra良好的可扩放性，被Digg、Twitter等知名Web 2.0网站所采纳，成为了一种流行的分布式结构化数据存储方案
* [Couchbase](https://github.com/couchbase/manifest) - 为Web时代而生的开源数据库
* [CrateDB](https://github.com/crate/crate) - CrateDB是一个分布式SQL数据库，可以轻松实时存储和分析大量机器数据
* [Druid](https://github.com/apache/incubator-druid) - Apache Druid(孵化中)是一个用于事件驱动数据的高性能列簇数据库
* [FoundationDB](https://github.com/apple/foundationdb) - FoundationDB是一个分布式数据库，旨在处理跨商用服务器群集的大量结构化数据. 它将数据组织为有序的键值存储，并为所有操作使用ACID事务。它特别适用于读/写工作负载，但对写入密集型工作负载也具有出色的性能。用户使用API​​语言绑定与数据库交互
* [Hadoop](https://github.com/apache/hadoop) - Apache Hadoop使用简单的编程模型跨计算机集群分布式处理大型数据集
* [Hazelcast](https://github.com/hazelcast/hazelcast) - 企业级的开源框架, 是一款功能丰富且对开发人员友好的内存数据网格解决方案
* [Infinispan](https://github.com/infinispan/infinispan) - 一个开源数据网格平台和高度可扩展的NoSQL云数据存储
* [MariaDB](https://github.com/MariaDB/server) - MariaDB server是社区开发的MySQL server的分支,由原始MySQL团队的核心成员发起
* [Fescar](https://github.com/alibaba/fescar) - 阿里出品的分布式事务解决方案，具有高性能和易于使用的微服务架构
* [MongoDB](https://github.com/mongodb/mongo) - 一个文档数据库, 由C++撰写而成
* [MySQL](https://github.com/mysql/mysql-server) - 世界上最流行的开源数据库
* [Neo4j](https://github.com/neo4j/neo4j) - 高性能的图形数据库，具有成熟和强大的数据库所需的所有功能，如友好的查询语言和ACID事务
* [noms](https://github.com/attic-labs/noms) - 一款灵感来自于Git的去中心化的数据库

## 缓存
* [redis](https://github.com/antirez/redis) - 可以当成数据库, 缓存, 消息队列使用的内存数据结构存储工具.
* [ehcache](https://github.com/ehcache/ehcache3) - 号称使用最为广泛的java缓存

## 流&消息
* [Kafka](https://github.com/apache/kafka) - 隶属于Apache的分布式流平台
* [RocketMQ](https://github.com/apache/rocketmq) - 隶属于Apache的分布式消息跟流平台, 低延迟, 高性能, 高可靠, 万亿级别容量, 动态扩展
* [ActiveMQ](https://github.com/apache/activemq) - 隶属于Apache的高性能消息队列
* [NATS Server](https://github.com/nats-io/gnatsd) - NATS Server是一个简单, 高性能的开源消息系统, 适用于云原生应用程序, 物联网消息传递和微服务架构。
* [Heron](https://github.com/apache/incubator-heron) - Apache Heron(孵化中)是一款来自Twitter的实时, 分布式, 具有容错性的流处理引擎
* [NiFi](https://github.com/apache/nifi) - Apache NiFi是一个易于使用, 功能强大且可靠的系统, 用于处理和分发数据
* [Spark](https://github.com/apache/spark) - Apache Spark是一种快速通用的大数据集群计算系统. 提供Scala, Java, Python和R的高级API,以及支持数据分析的通用计算图的优化引擎
* [Storm](https://github.com/apache/storm) - Apache Storm是一个分布式实时计算系统. 类似于Hadoop提供一组用于批处理的通用基元, Storm以此处理实时计算
* [Beam](https://github.com/apache/beam) - Apache Beam是一个统一的模型，用于定义批处理和流数据并行处理管道，以及一组特定于语言的SDK，用于构建管道和Runners，用于在分布式处理后端上执行它们，包括Apache Apex，Apache Flink，Apache Spark和Google Cloud Dataflow。
* [CloudEvents](https://github.com/cloudevents/spec) - CloudEvents是一项新的开放规范，用于对事件数据提供一致的描述标准. 该开放规范由 CNCF下设的 无服务器工作组（Serverless Working Group）提出，且CNCF已与多家云服务和云提供商建立了合作伙伴关系
* [Flink](https://github.com/apache/flink) - Apache Flink是一个开源流处理框架，具有强大的流和批处理功能
* [Open Messaging](https://github.com/openmessaging/openmessaging-java) - OpenMessaging, 目的在于建立行业指南并且为消息传递，流媒体规范，为财务，电子商务，物联网和大数据领域提供通用框架. 设计原则是分布式异构环境中面向云，简单，灵活和独立于语言的原则. 符合这些规范将有可能在所有主要平台和操作系统上开发异构消息传递应用程序
* [Pachyderm](https://github.com/pachyderm/pachyderm) - 数据版本控制，数据管道和数据沿袭工具
* [Pulsar](https://github.com/apache/pulsar) - Pulsar是一个分布式pub-sub消息传递平台，具有非常灵活的消息传递模型和直观的客户端API

## 应用定义&镜像构建
* [Helm](https://github.com/helm/helm) - 一个Kubernetes包管理器, CNCF项目
* [Brooklyn](https://github.com/apache/brooklyn-server) - Apache旗下开源框架, 用于建模, 部署和管理使用声明式YAML蓝图定义的分布式应用程序
* [Buildpacks](https://github.com/buildpack/pack) - Buildpacks是可插拔的模块化工具，可将源代码转换为OCI映像
* [Docker Compose](https://github.com/docker/compose) - Compose是一个用于定义和运行多容器Docker应用程序的工具。使用Compose，您可以使用Compose文件来配置应用程序的服务。然后，使用单个命令，您可以从配置中创建并启动所有服务
* [Draft](https://github.com/azure/draft) - 一款用于开发人员在Kubernetes上创建云原生应用程序的工具
* [Habitat](https://github.com/habitat-sh/habitat) - 可创建独立于平台的构建工件，并提供内置的部署和管理功能

## 搜索引擎
* [elasticsearch](https://github.com/elastic/elasticsearch) - 支持分布式的Restful的搜索引擎

## 调度&编排
* [kubernetes](https://github.com/kubernetes/kubernetes) - Kubernetes是一个开源系统, 用于管理多个主机上的容器化应用程序;提供应用程序部署, 维护和扩展的基本机制
* [elastic-job](https://github.com/elasticjob/elastic-job-lite) - Elastic-Job是一个分布式调度解决方案, 由两个相互独立的子项目Elastic-Job-Lite和Elastic-Job-Cloud组成.
* [flink](https://github.com/apache/flink) - 隶属于Apache的流处理框架,拥有强大的流处理以及批量处理的能力.
* [quartz](https://github.com/quartz-scheduler/quartz) - 功能丰富的,几乎可以与任何java程序集成的调度框架
* [xxl-job](https://github.com/xuxueli/xxl-job) - 分布式任务调度平台XXL-JOB

## 服务协调&发现
* [coredns](https://github.com/coredns/coredns) - CoreDNS(Go语言编写)是一个链接插件的DNS服务器, 每个插件都执行DNS功能。
* [zookeeper](https://github.com/apache/zookeeper) apache旗下的分布式服务协调框架
* [etcd](https://github.com/etcd-io/etcd) 一个可依赖的分布式key-value存储系统, 用于分布式环境下保存关键数据
* [Consul](https://github.com/hashicorp/consul) - Consul是一种服务发现和配置工具。 Consul具有分布式，高可用性和极高的可扩展性
* [Nacos](https://github.com/alibaba/nacos) - 阿里出品的一款易于使用的动态服务发现, 配置和服务管理平台, 用于构建云本机应用程序。

## 服务代理
* [envoy](https://github.com/envoyproxy/envoy) - Envoy是一个开源服务代理, 专为云应用而设计

## API网关
* [3scale](https://github.com/3scale/apicast) - APIcast是一个建立在NGINX之上的API网关. 它是Red Hat 3scale API管理平台的一部分

## ServiceMesh
* [linkerd](https://github.com/linkerd/linkerd) - Linkerd旨在透明地向所有服务间通信添加服务发现, 负载平衡, 故障处理, 检测和路由, 使应用程序变得安全可靠

## 云原生存储
* [rook](https://github.com/rook/rook) - Rook是Kubernetes的开源云本地存储协调器，为各种存储解决方案提供平台，框架和支持，以便与云原生环境本地集成

## 容器
* [containerd](https://github.com/containerd/containerd) - 一个开放且可靠的容器运行时

## 云原生网络
* [cni](https://github.com/containernetworking/cni) - Container Network Interface - 用于Linux容器的网络体系

## 自动化&配置
* [ansible](https://github.com/ansible/ansible) - IT自动化的平台, 使系统跟程序更加容易部署
* [disconf](https://github.com/knightliao/disconf) - 分布式配置管理平台
* [mgmt](https://github.com/purpleidea/mgmt) - 号称下一代的配置管理平台
* [QConf](https://github.com/Qihoo360/QConf) - 奇虎的分布式配置管理平台
* [apollo](https://github.com/ctripcorp/apollo) - 携程框架部门研发的分布式配置中心, 能够集中化管理应用不同环境、不同集群的配置, 配置修改后能够实时推送到应用端, 并且具备规范的权限、流程治理等特性, 适用于微服务配置管理场景
* [BOSH](https://github.com/cloudfoundry/bosh) - Bosh是一款用于发布, 部署, 生命周期管理以及监控的开源工具
* [Portainer](https://github.com/portainer/portainer) - Portainer是一个轻量级管理UI，允许您轻松管理不同的Docker环境（Docker主机或Swarm集群）
* [confd](https://github.com/kelseyhightower/confd) - confd是一个轻量级的配置管理工具, 通过读取存储在etcd,consul,redis等的数据来保持本地配置文件最新

## 安全&合规
* [Shiro](https://github.com/apache/shiro) - 隶属于apache的功能强大的java安全框架
* [Knox](https://github.com/pinterest/knox) - Knox用于管理其他服务中使用到的秘钥相关信息

## 监控
* [prometheus](https://github.com/prometheus/prometheus) - CNCF项目, 用于监控其他系统或服务. 它以给定的时间间隔从目标收集指标，根据规则进行评估，显示结果，如果达到某些监控条件, 还可以触发警报

## 日志
* [log4j](https://github.com/apache/log4j) - apache旗下的老牌日志工具

## 测试
* [selenium](https://github.com/SeleniumHQ/selenium) - 自动化浏览器测试框架
* [mockito](https://github.com/mockito/mockito) - Java体系中用于单元测试的最受欢迎的Mocking工具

## 混沌工程
* [chaostoolkit](https://github.com/chaostoolkit/chaostoolkit) - 为社区所需的各种形式的混沌工程工具提供免费，开放和社区驱动的工具包和API

## 插件&工具
* [guava](https://github.com/google/guava) - google出品的非常好用的Java工具包
* [netty](https://github.com/netty/netty) - 事件驱动的支持异步的网络框架
* [hystrix](https://github.com/Netflix/Hystrix) - Netflix出品的熔断器, 目前已停止更新
* [resilience4j](https://github.com/resilience4j/resilience4j) - 轻量级的熔断器, 设计上受到Hystrix的启发, 但专为Java 8和函数式编程而设计
* [uid-generator](https://github.com/baidu/uid-generator) - 百度出品的基于snowflake的唯一Id生成器
* [fastjson](https://github.com/alibaba/fastjson) - 阿里出品的解析/生成JSON的java框架
* [swagger](https://github.com/swagger-api/swagger-ui) - java API管理工具
* [protobuf](https://github.com/google/protobuf) - google出品的平台无关,语言无关的序列化工具
* [cqengine](https://github.com/npgall/cqengine) - 可以在Java的collection中进行SQL-like查询的工具
* [jetcache](https://github.com/alibaba/jetcache) - 阿里出品的Java缓存框架, "用起来比Spring Cache更方便"
* [vert.x](https://github.com/eclipse/vert.x) - JVM上用于开发reactive程序的工具包
* [mapper](https://github.com/abel533/Mapper) - MyBatis 通用 Mapper
* [tcc-transaction](https://github.com/changmingxie/tcc-transaction) - TCC型事务java实现
* [druid](https://github.com/alibaba/druid) - 阿里出品的号称"为监控而生"的数据库连接池
* [fast-syntax-highlighting](https://github.com/zdharma/fast-syntax-highlighting) - zsh的语法高亮插件
* [nosqlclient](https://github.com/nosqlclient/nosqlclient) - mongodb的客户端
* [mybatis-generator-gui](https://github.com/zouzg/mybatis-generator-gui) mybatis generator的GUI工具
* [git_commit_template](https://github.com/joelparkerhenderson/git_commit_template) - 一个git message的模板
* [gitignore.io](https://github.com/joeblau/gitignore.io) - 可以方便的自定义.gitignore文件
* [shadowsocks](https://github.com/shadowsocks) - 这个无需介绍了,懂的自然都懂
* [source-code-pro](https://github.com/adobe-fonts/source-code-pro) - Adobe开源的编程字体
* [antlr4](https://github.com/antlr/antlr4) - ANTLR是一个功能强大的解析器生成器,用于读取,处理,执行, 转换结构化文本或二进制文件
* [etcdkeeper](https://github.com/evildecay/etcdkeeper) - 一款etcd的web ui工具, 支持etcd v3
* [kops](https://github.com/kubernetes/kops) - Kubernetes Operations（kops） - 生产级的K8s安装，升级和管理工具	
* [boot2docker](https://github.com/boot2docker/boot2docker) - Boot2Docker是一个轻量级Linux发行版，专门用于运行Docker容器。它可以完全在RAM中运行，下载约45MB并启动速度很快
* [FiraCode](https://github.com/tonsky/FiraCode) - 适合编程的等宽开源字体, 有retina版本
* [error-prone](https://github.com/google/error-prone) - Google出品的一款Java静态分析工具, 可以在编译时捕获常见错误

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
* [skill-map](https://github.com/TeamStuQ/skill-map) - 程序员技能图谱
* [advanced-java](https://github.com/doocs/advanced-java) - 互联网 Java 工程师进阶知识完全扫盲
* [gopl-zh](https://github.com/golang-china/gopl-zh) - Go语言圣经中文版
* [prometheus_practice](https://github.com/songjiayang/prometheus_practice) - 包括 Prometheus 安装, 基础监控, 常用 exporter, 性能优化和大量实战经验
* [和我一步步部署 kubernetes 集群](https://github.com/opsnull/follow-me-install-kubernetes-cluster) - 本系列文档介绍使用二进制部署最新 kubernetes v1.10.4 集群的所有步骤，而不是使用 kubeadm 等自动化方式来部署集群
* [Go四十二章经](https://github.com/ffhelicopter/Go42) - 作者前言 : 纯粹是因为开发过程中碰到过的一些问题，踩到过的一些坑，感觉在Go语言学习使用过程中，有必要深刻理解这门语言的核心思维、清晰掌握语言的细节规范以及反复琢磨标准包代码设计模式，于是才有了这本书
* [Netty learning](https://github.com/code4craft/netty-learning) - Netty源码解析

## 文档汉化
* [kafka-doc-zh](https://github.com/apachecn/kafka-doc-zh/) - Kafka 中文文档
* [redis](https://github.com/huangz1990/redis) - Redis Command Reference全文的中文翻译版
* [spring-5-framework-doc](https://github.com/lfvepclr/spring-5-framework-doc) - Spring 5文档翻译
* [java-nio-zh](https://github.com/avenwu/java-nio-zh) - 汉化的Java NIO教程
* [istio中文文档](https://github.com/doczhcn/istio) - Istio官方文档中文版
* [build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang) - 包含多语言(包含中文)版本的GO教程
* [Netty In Action 中文版](https://github.com/ReactivePlatform/netty-in-action-cn) - Netty In Action中文版

## 面试相关
* [Back-End-Developer-Interview-Questions](https://github.com/arialdomartini/Back-End-Developer-Interview-Questions) - 后端开发面试题
* [The-Art-Of-Programming-By-July](https://github.com/julycoding/The-Art-Of-Programming-By-July) - July的<<编程之法：面试和算法心得>>
* [hunter](https://github.com/lietoumai/Hunter) - 面试技巧相关
* [interview-notebook](https://github.com/CyC2018/Interview-Notebook) - 技术面试需要掌握的基础知识
* [interviews](https://github.com/kdn251/interviews) - 找工作需要了解的基础技术
* [2018-Java-Interview](https://github.com/xbox1994/2018-Java-Interview) - 2018年几个大厂的面试宝典

## 其他资源
* [awesome-java](https://github.com/akullpp/awesome-java) - 整理了相当多java生态圈的相关资源
* [awesome-chaos-engineering](https://github.com/dastergon/awesome-chaos-engineering) - 收集了优秀的混沌工程相关的信息
* [awesome-scalability](https://github.com/binhnguyennus/awesome-scalability) - 整理了相当多的高扩展,高可用,高性能等的设计模式
* [awesome-blockchain-cn](https://github.com/chaozh/awesome-blockchain-cn) - 收集所有区块链(BlockChain)技术开发相关资料, 包括Fabric和Ethereum开发资料
* [awesome-kubernetes](https://github.com/ramitsurana/awesome-kubernetes) - 优秀的k8s资料集
* [cloud-native-slides-share](https://github.com/rootsongjc/cloud-native-slides-share) - 收集了大量的cloud native相关的大会资料,开源书籍以及类似信息
* [IntelliJ-IDEA-Tutorial](https://github.com/judasn/IntelliJ-IDEA-Tutorial) - IDEA教程
* [tenant-point](https://github.com/soulteary/tenant-point) - 租房要点, 适用于北上广深杭
* [English-level-up-tips-for-Chinese](https://github.com/byoungd/English-level-up-tips-for-Chinese) - 高效学习英语
* [lianjia-beike-spider](https://github.com/jumper2014/lianjia-beike-spider) - 主要城市的房价爬虫

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
* [芋道源码](http://www.iocoder.cn/) - 作者通过阅读大量源码拆解, 分析各种常见框架

## 游戏
* [RetroArch](https://github.com/libretro/RetroArch) - 跨平台游戏模拟器
* [Citra](https://github.com/citra-emu/citra) - 3DS模拟器
* [Dolphin](https://github.com/dolphin-emu/dolphin) - Wii模拟器
* [Cemu](http://cemu.info/) - Wii U模拟器
* [Ryujinx](https://github.com/Ryujinx/Ryujinx) - 任天堂switch模拟器
* [PPSSPP](https://github.com/hrydgard/ppsspp) - PSP模拟器
* [ePSXe](http://www.epsxe.com/) - PS模拟器
* [PCSX2](https://pcsx2.net/) - PS2模拟器
* [RPCS3](https://github.com/RPCS3/rpcs3) - PS3模拟器
* [PCSX4](https://github.com/pcsx4) - PS4模拟器