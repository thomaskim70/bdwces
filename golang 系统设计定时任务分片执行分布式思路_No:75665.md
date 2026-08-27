最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.grlannz.asia/blog/6139178.sHtMl

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.grlannz.asia/blog/4338354.sHtMl

原标题：快速入门环境区分：开发、测试、生产环境
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.grlannz.asia/blog/6862869.sHtMl

原标题：实战：Nginx实现文件限速下载配置实践
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.grlannz.asia/blog/6824685.sHtMl

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://book.grlannz.asia/blog/3294135.sHtMl

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.grlannz.asia/blog/8966058.sHtMl

原标题：golang 系统设计数据库连接池调优实践
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.grlannz.asia/blog/1352021.sHtMl

原标题：项目实践：灰度发布简易方案落地实践
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.grlannz.asia/blog/0802751.sHtMl

原标题：5分钟快速搭建个人技术文档站点
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.grlannz.asia/blog/2658750.sHtMl

原标题：golang 系统设计读写分离延迟业务兼容
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.grlannz.asia/blog/0597209.sHtMl

原标题：WSL 文件权限访问异常修复
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://book.grlannz.asia/blog/9664809.sHtMl

原标题：实践：分布式事务本地模拟验证实践
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.grlannz.asia/blog/2670389.sHtMl

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.grlannz.asia/blog/2793190.sHtMl

原标题：安全笔记：文件下载接口路径校验安全
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.grlannz.asia/blog/2067523.sHtMl

原标题：开发代理服务网络限制解决
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.grlannz.asia/blog/6200325.sHtMl

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.grlannz.asia/blog/5329098.sHtMl

原标题：零基础理解数据库事务基础ACID概念
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.grlannz.asia/blog/5097239.sHtMl

原标题：部署实践：DockerCompose管理多服务环境
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.grlannz.asia/blog/5459387.sHtMl

原标题：异步任务堆积消费能力优化
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.grlannz.asia/blog/9067421.sHtMl

原标题：golang kafka 生产者参数调优
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.grlannz.asia/blog/9301235.sHtMl

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.grlannz.asia/blog/9383611.sHtMl

原标题：Practice：实现定时任务动态启停管理接口
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.grlannz.asia/blog/7112510.sHtMl

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://book.grlannz.asia/blog/0138652.sHtMl

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.grlannz.asia/blog/1952462.sHtMl

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.grlannz.asia/blog/6001213.sHtMl

原标题：轻量 API 后端接口服务快速开发
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.grlannz.asia/blog/8829359.sHtMl

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.grlannz.asia/blog/3724391.sHtMl

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.grlannz.asia/blog/3231009.sHtMl

原标题：golang redis 分布式锁 redisson 思路
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.grlannz.asia/blog/7102870.sHtMl

原标题：部署实践：服务器时间同步chrony配置
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.grlannz.asia/blog/2233835.sHtMl

原标题：快速入门简单签名校验实现思路
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://book.grlannz.asia/blog/3347550.sHtMl

原标题：golang csv 读写批量数据处理
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.grlannz.asia/blog/1642635.sHtMl

原标题：实战：Redis管道批量操作性能优化实践
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.grlannz.asia/blog/3764292.sHtMl

原标题：golang k8s 命名空间资源隔离方案
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.grlannz.asia/blog/3866117.sHtMl

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.grlannz.asia/blog/6254331.sHtMl

原标题：golang redis lua 脚本原子操作
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.grlannz.asia/blog/7369234.sHtMl

原标题：数据库分表路由写入分片修正
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.grlannz.asia/blog/7894340.sHtMl

原标题：Hands‑on：简易请求转发代理中间件实现
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.grlannz.asia/blog/2493028.sHtMl

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.grlannz.asia/blog/5670570.sHtMl

原标题：golang 系统设计采样策略降低链路存储开销
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.grlannz.asia/blog/9950826.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.grlannz.asia/blog/4440136.sHtMl

原标题：golang minio 预签名 url 临时访问
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.grlannz.asia/blog/8142095.sHtMl

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.grlannz.asia/blog/2339118.sHtMl

原标题：nestjs 框架模块化项目搭建
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://book.grlannz.asia/blog/7915570.sHtMl

原标题：golang 大文件读取内存优化
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.grlannz.asia/blog/1487945.sHtMl

原标题：Redis 内存淘汰策略数据防丢失
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.grlannz.asia/blog/3701237.sHtMl

原标题：golang 表单文件大小限制配置
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.grlannz.asia/blog/7431013.sHtMl

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.grlannz.asia/blog/0534795.sHtMl

原标题：代码格式化工具团队统一风格
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.grlannz.asia/blog/8693875.sHtMl

原标题：golang 简单爬虫请求防封禁
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.grlannz.asia/blog/5243758.sHtMl

原标题：DevOps：容器网络模式选型与坑点总结
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.grlannz.asia/blog/1916334.sHtMl

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.grlannz.asia/blog/9133647.sHtMl

原标题：从零搭建简单的身份登录模拟示例
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.grlannz.asia/blog/1577540.sHtMl

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.grlannz.asia/blog/5943252.sHtMl

原标题：golang 系统设计消息大小限制业务处理方案
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.grlannz.asia/blog/1332535.sHtMl

原标题：批量异步处理系统业务落地
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.grlannz.asia/blog/1870783.sHtMl

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.grlannz.asia/blog/5212605.sHtMl

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.grlannz.asia/blog/3136635.sHtMl

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.grlannz.asia/blog/8973117.sHtMl

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.grlannz.asia/blog/1866225.sHtMl

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.grlannz.asia/blog/5014586.sHtMl

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.grlannz.asia/blog/9045906.sHtMl

原标题：golang 系统设计限流服务架构讲解
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.grlannz.asia/blog/0718402.sHtMl

原标题：golang 系统设计配置多环境隔离方案落地
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://book.grlannz.asia/blog/9512827.sHtMl

原标题：Practice：实现接口防重提交组件实践
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.grlannz.asia/blog/8473589.sHtMl

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.grlannz.asia/blog/9536783.sHtMl

原标题：Nginx 缓冲区调优大文件上传
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.grlannz.asia/blog/5634419.sHtMl

原标题：MySQL 慢查询索引优化实战
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.grlannz.asia/blog/8123031.sHtMl

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.grlannz.asia/blog/0084681.sHtMl

原标题：golang kafka 消费者组原理讲解
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.grlannz.asia/blog/5723848.sHtMl

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.grlannz.asia/blog/3045790.sHtMl

原标题：方案对比：定时任务框架选型与架构对比
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.grlannz.asia/blog/1104090.sHtMl

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.grlannz.asia/blog/4519163.sHtMl

原标题：golang ci 流水线漏洞扫描依赖检查
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.grlannz.asia/blog/5383864.sHtMl

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.grlannz.asia/blog/2556058.sHtMl

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.grlannz.asia/blog/6791377.sHtMl

原标题：接口压测定位系统性能瓶颈
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.grlannz.asia/blog/8846317.sHtMl

原标题：golang github actions 完整工作流示例
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.grlannz.asia/blog/5572536.sHtMl

原标题：golang 静态文件服务搭建教程
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.grlannz.asia/blog/0113944.sHtMl

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.grlannz.asia/blog/5238890.sHtMl

三、实战开发｜Practice
原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://book.grlannz.asia/blog/8734493.sHtMl

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.grlannz.asia/blog/5695739.sHtMl

原标题：golang 系统设计分布式锁选型对比
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.grlannz.asia/blog/7107332.sHtMl

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://book.grlannz.asia/blog/9097132.sHtMl

原标题：golang 系统设计短链接服务实现思路
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.grlannz.asia/blog/6172684.sHtMl

原标题：快速入门gRPC基础概念与简单示例
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.grlannz.asia/blog/0401727.sHtMl

原标题：Git LFS 大文件推送失败解决
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.grlannz.asia/blog/4472714.sHtMl

原标题：gitignore 文件编写过滤规则
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://book.grlannz.asia/blog/1146995.sHtMl

原标题：实战：容器内执行调试排错完整实操流程
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.grlannz.asia/blog/9187094.sHtMl

原标题：开发复盘：批量任务进度持久化实现方案
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://book.grlannz.asia/blog/1580938.sHtMl

原标题：golang 系统设计日志规范结构化日志落地
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.grlannz.asia/blog/5976846.sHtMl

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.grlannz.asia/blog/1819844.sHtMl

原标题：golang jwt 过期刷新 token 实现
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.grlannz.asia/blog/5249993.sHtMl

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.grlannz.asia/blog/4550171.sHtMl

原标题：golang consul 健康检查服务注册
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.grlannz.asia/blog/2451636.sHtMl

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.grlannz.asia/blog/7607013.sHtMl

原标题：golang 时间时区处理避坑指南
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.grlannz.asia/blog/7446461.sHtMl

原标题：rebase 操作防止代码丢失
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.grlannz.asia/blog/8172594.sHtMl

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.grlannz.asia/blog/2650766.sHtMl

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.grlannz.asia/blog/7116796.sHtMl

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.grlannz.asia/blog/2314122.sHtMl

原标题：golang k8s 监控 prometheus 部署
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.grlannz.asia/blog/9682540.sHtMl

原标题：零基础理解幂等性基础概念与场景
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.grlannz.asia/blog/4573770.sHtMl

原标题：golang docker 网络模式桥接 host
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.grlannz.asia/blog/0773513.sHtMl

原标题：新手指南：看懂开源项目的Issue与PR
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.grlannz.asia/blog/9398622.sHtMl

原标题：从零搭建简单定时任务demo
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.grlannz.asia/blog/5211522.sHtMl

原标题：golang ci 流水线漏洞扫描依赖检查
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.grlannz.asia/blog/6168932.sHtMl

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.grlannz.asia/blog/6134385.sHtMl

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.grlannz.asia/blog/7230917.sHtMl

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.grlannz.asia/blog/2594168.sHtMl

原标题：golang ci 流水线单元测试集成测试
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.grlannz.asia/blog/0508558.sHtMl

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.grlannz.asia/blog/6278116.sHtMl

原标题：golang 系统设计数据库扩容几种方式
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.grlannz.asia/blog/3963568.sHtMl

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.grlannz.asia/blog/8306280.sHtMl

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.grlannz.asia/blog/0875022.sHtMl

原标题：golang 数据库慢查询监控实现
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.grlannz.asia/blog/7161105.sHtMl

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.grlannz.asia/blog/6486538.sHtMl

原标题：开发记录：业务错误告警邮件通知组件实践
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.grlannz.asia/blog/4202670.sHtMl

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.grlannz.asia/blog/0586328.sHtMl

原标题：Hands‑on：简易事件驱动架构原型开发
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.grlannz.asia/blog/8829792.sHtMl

四、架构设计｜Architecture
原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.grlannz.asia/blog/3273571.sHtMl

原标题：DNS 解析异常第三方调用故障
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.grlannz.asia/blog/4286834.sHtMl

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://book.grlannz.asia/blog/1188539.sHtMl

原标题：入门实践：简易进度条CLI工具实现demo
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.grlannz.asia/blog/0313687.sHtMl

原标题：golang ip 限流黑名单实现方案
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://book.grlannz.asia/blog/5923078.sHtMl

原标题：前后端会话登录状态持久化
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.grlannz.asia/blog/6547875.sHtMl

原标题：golang mysql 分表自增 id 方案
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.grlannz.asia/blog/9319548.sHtMl

原标题：golang es 批量 bulk 操作性能调优
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.grlannz.asia/blog/7215230.sHtMl

原标题：golang redis pipeline 原子性说明
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.grlannz.asia/blog/6411485.sHtMl

原标题：golang 系统设计定时任务动态启停配置方案
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.grlannz.asia/blog/3682348.sHtMl

原标题：golang 系统设计最小权限原则落地实践
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.grlannz.asia/blog/6209654.sHtMl

原标题：golang 系统设计接口超时设计原则梳理
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.grlannz.asia/blog/6238111.sHtMl

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.grlannz.asia/blog/0409502.sHtMl

原标题：部署实践：容器时区统一配置解决方案
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.grlannz.asia/blog/9656784.sHtMl

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.grlannz.asia/blog/2335191.sHtMl

原标题：Nginx 透传真实客户端 IP 配置
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.grlannz.asia/blog/2805225.sHtMl

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.grlannz.asia/blog/4908262.sHtMl

原标题：golang 单元测试 table‑driven
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.grlannz.asia/blog/9057515.sHtMl

?
