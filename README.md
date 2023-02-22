## <center><strong>康宣鹏 应聘职位:PHP工程师 工作5年</strong></center>
### 联系方式

- 手机：158 8932 5915
- Email：me@kangxuanpeng.com / kangxuanpeng@163.com

---

### 个人信息

- 康宣鹏/男/1996
- 本科/广东财经大学/工商管理专业
- 大专/深圳职业技术学院/计算机信息管理专业
- 工作年限：5年
- 求职岗位：PHP 工程师
- 工作状态：已离职，近期可到岗

---

### 自我评价

- 熟练掌握 Laravel、 Yii、ThinkPHP 等主流框架；
- 熟练使用 Linux 操作系统，能做基本的运维操作，熟悉 Docker 操作；
- 熟悉大型 WEB 架构设计和性能优化，有高并发项目优化经验；
- 熟悉 MySQL 使用及性能优化，有日增千万数据级别 SQL 优化经验，对 Redis 有较深入掌握；
- 熟练掌握 SVN、Git 版本控制工具；
- 拥有良好的代码习惯，结果清晰，命名规范，逻辑性强；
- 善于学习，能独立解决问题，具有良好的沟通能力和团队合作精神；
- 有较强的自我驱动能力，善于给自己和同事制定学习计划。

---

### 工作经历

#### 深圳市智连网科技有限公司 (2020年3月~2022年11月)
##### 职位：PHP 负责人
##### 工作内容

- 配合产品经理参与需求评审，分解安排开发任务，统筹部门成员协同工作，保证需求按时按质量落实与验收
- 跟进并参与游戏平台项目迭代功能开发、发布上线流程
- 规范开发流程，制定代码质量要求，把关上线标准、流程
- 线上问题跟进处理，添加监控程序保证正常运行(服务器性能、代码质量、业务指标)
- 事故排查分析、总结经验复盘，组织知识分享交流会
- 服务器集群架构调整升级，设计容灾方案，以应对业务性能压力以及 DDoS 攻击
- 根据业务需要开发手脚架、增加框架新特性，提升开发效率
- Docker 容器搭建服务器环境，统一开发与线上环境差异
- 分析系统瓶颈，解决疑难问题，技术难题攻坚，对系统进行性能调优
- 根据业务情况参与系统技术选型规划设计，用技术方案解决实际问题

##### 海外休闲游戏聚合平台 (```2020.03-2022.11```)

一款面对海外的休闲游戏平台，提供多种游戏服务为基础，对接多家游戏⼚商及⾃研游戏，为玩家提供多元化，全⽅位互联⽹游戏。

担任角色：参与项目筹备阶段功能研发；上线阶段项目部署；用户增长阶段服务器优化、运维；稳定营收阶段实现项目运营自动化、监控系统协助维护。

项目细则：

- 负载均衡分布式高可用集群架构；服务器架构设计、调优及问题定位分析
- MySql 主从集群，实现读写分离；热数据 NoSQL 缓存化，降低数据库访问压力
- 数据库专项优化；分库分表、SQL 调优 `分表后单表日增达4千万以上`
- API 接口响应时间优化，耗时任务采用消息队列实现错峰异步化
- 规范设计 API 交互规则；产出前后端、三方 API 文档
- crontab 定时任务、常驻队列 Cli 进程实现运营自动化需求
- 谷歌包服务支撑以及业务数据监控系统规则提出并完善
- 对接多家三方支付，独立设计为聚合支付平台 LotusPay 并对四方开放

##### 高流量大数据增长问题处理

游戏平台项目业务上升期迎来流量突增引发一系列问题，包括请求卡顿、业务服务器 CPU 暴涨、MySQL 服务器 CPU 占用异常。

- 慢查询 SQL 优化调优，提升请求响应速度
- 热数据增加 Redis 缓存层，减少 MySQL 访问次数
- 增加独占锁，避免用户重复刷请求带来异常问题
- 耗时任务改为异步执行，高频业务功能高峰流量控制，减轻峰值性能压力
- 调整服务器配置(Nginx、PHP-FPM 等)，最大化利用服务器性能
- 增加服务器集群，分摊服务器压力；MySQL 主从复制读写分离，减轻单台机器负载过高问题


##### DDoS 攻击应对方案

项目遭遇 DDoS 流量攻击，直接把服务器打入阿里云黑洞保护，无法与外界通信；
后续采用阿里云 Anti-DDoS 高防方案处理，之后项目稳定。

- 释放业务服务器、MySQL 服务器的公网 IP，避免公网端口暴露带来被攻击风险
- 入站请求流量经 Anti-DDoS 高防服务器转发到 SLB 负载均衡反代转发到业务服务器
- 出站流量进 NAT 网关代理连接外面实现访问外部服务
- 内部服务统一用阿里云内网 IP 通信，严格管理安全组规则

##### 代码质量规范制定

- 编码过程中采用统一的 PSR 标准规范，规范的代码风格规则
- 采用 PHP_CodeSniffer 检测代码风格，统一 inspection 规则，phpcbf 进行问题修复
- 统一数据库设计规范

##### Docker 自定义镜像，统一环境配置

将服务器上各环境拓展等编译成自定义 Docker 镜像，以应对服务器迁移、开发环境的配置差异带来的无意义排查工作。

- 将单个服务编译为镜像，预设常用配置方便使用
- Docker-Compose 编排各镜像，一键配置启动所需相关服务

##### 自建 PHP 框架用于公司新项目

根据公司新规划项目需求，开发了自建极轻量框架开发；升级依赖软件的版本，使用新特性；以达到较好的性能消耗表现。

- Docker-Compose 容器镜像编排 PHP `8.0.23`、 Mysql `8.0`、Redis `7.0.2`、Nginx `1.22.0`
- 底层支持读写分离，业务上分库分表以满足大数据量之后的性能压力
- 路由、中间件管理实现前后端 API 加密响应，请求性能消耗分析记录
- 事件监听模式，异步任务处理(消息中间件)
- Websocket 实现双向通信，Swoole 常驻 HTTP 服务器提升响应时间(类 rpc 概念)
- Composer 包发布，引入管理

#### 深圳顺为管理顾问有限公司 (2019年2月~2019年11月)
##### 职位：PHP 工程师
##### 工作内容
- 迭代公司自研APP：哪哪 APP
- 对新需求进行功能评估
- 配合安卓、IOS端开发和维护新功能
- 开发维护后台管理平台系统功能

##### 哪哪 App (```2019.02-2019.11```)

哪哪 App 是一个有地理位置特色的移动互联网社交应用。
结合地理位置展示动态和红包范围领取功能，对本地线下商家提供推广渠道；  
用户获利现金可提现，商家获取推广收益达到三赢效果

担任角色：需求评估、后端功能设计开发、配合App端完成用户交互、后台管理页面开发、功能系统维护升级  
贡献成果：
- 建立邀请分佣机制 ```被邀请用户在总用户中占比80%```
- 用户提现到支付宝短时间内自动到账 ```与用户充值完成交互流程，免除人工手动转账繁琐的操作```
- 商家广告权重机制的制定 
- 建立缓存机制 ```缓解数据库压力```
- 建立用户风控监测机制 ```防止用户多地登录```
- 资源文件启用转移到七牛云cdn，减轻服务器访问压力
- 用户设置备注
- 处理并发问题  ```并发抢红包问题，优化用户频繁重复抢红包```
- 返现活动 ```用户参与商城活动，购买商品获得返现，每天活跃即可获得返现，大幅增加了用户粘性```
- 高频操作异步执行 ```减轻服务器压力，譬如增加动态阅读量、消息推送 and so on```
- 扫码付款 ```为线下商家增加扫码收款功能```
- 加入定制化功能权限分配 ```为用户分配开放使用App定制功能```

#### 深圳乐橙互娱科技有限公司 (2018年3月~2018年12月)
##### 职位：PHP 工程师
##### 工作内容
- 独立负责维护升级游戏平台 SDK、SDK 后台管理系统的正常运行
- 搭建迭代新游戏预热宣传页面、游戏活动页面
- 维护游戏平台官网、公司官网
- 满足公司部门宣传网页、隐私政策页面等需求

#### 深圳市小美网络科技有限公司 (2017年6月~2018年1月)
##### 职位：PHP 工程师
##### 工作内容：
- 参与公司商城重构改版
- 负责公司商城版本迭代工作
- 开发了平台运营数据分析统计平台
- 对公司的 App 提供后端接口数据支撑
- 参与公司 OA 系统（erp）的功能设计与接口开发工作
- 参与数据分析平台系统开发

---

#### 主页地址

 - GitHub: [https://github.com/HongXunPan](https://github.com/HongXunPan)
 - Composer Packagist: [https://packagist.org/packages/hongxunpan](https://packagist.org/packages/hongxunpan)
 - Docker Hub: [https://hub.docker.com/u/hongxunpan](https://hub.docker.com/u/hongxunpan)

---

### 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。
