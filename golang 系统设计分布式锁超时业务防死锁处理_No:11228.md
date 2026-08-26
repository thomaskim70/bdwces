最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.x06jfh.asia/arts/339221.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.x06jfh.asia/arts/906099.Doc

原标题：nodejs 中间件模式原理剖析
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.x06jfh.asia/arts/646268.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.x06jfh.asia/arts/280664.Doc

原标题：空指针异常判空容错处理
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.x06jfh.asia/arts/182172.Doc

原标题：echarts 大数据渲染性能调优
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.x06jfh.asia/arts/841109.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.x06jfh.asia/arts/342855.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.x06jfh.asia/arts/930599.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.x06jfh.asia/arts/370350.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.x06jfh.asia/arts/504847.Doc

原标题：golang redis 集群 hash 槽讲解
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.x06jfh.asia/arts/115941.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.x06jfh.asia/arts/571855.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.x06jfh.asia/arts/112306.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.x06jfh.asia/arts/431632.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.x06jfh.asia/arts/926287.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.x06jfh.asia/arts/602965.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.x06jfh.asia/arts/126100.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.x06jfh.asia/arts/677892.Doc

原标题：Spring 事务传播机制配置生效
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.x06jfh.asia/arts/300728.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.x06jfh.asia/arts/952906.Doc

原标题：前端下载导出文件功能实现
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.x06jfh.asia/arts/954700.Doc

原标题：golang 静态文件服务搭建教程
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.x06jfh.asia/arts/181479.Doc

原标题：HTTP 状态码请求头完整梳理
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.x06jfh.asia/arts/687469.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.x06jfh.asia/arts/923766.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.x06jfh.asia/arts/463901.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.x06jfh.asia/arts/552182.Doc

原标题：golang ci 流水线环境变量管理方案
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.x06jfh.asia/arts/004878.Doc

原标题：golang k8s service 服务暴露几种类型
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.x06jfh.asia/arts/228336.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.x06jfh.asia/arts/869998.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.x06jfh.asia/arts/571413.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.x06jfh.asia/arts/203999.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.x06jfh.asia/arts/522882.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.x06jfh.asia/arts/117891.Doc

原标题：日志切割配置防止日志丢失
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.x06jfh.asia/arts/022629.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.x06jfh.asia/arts/885903.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.x06jfh.asia/arts/681041.Doc

原标题：golang 系统设计压测指标确定与分析
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.x06jfh.asia/arts/687933.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.x06jfh.asia/arts/359503.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.x06jfh.asia/arts/807794.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://wiki.x06jfh.asia/arts/048492.Doc


二、踩坑排错｜Troubleshooting
原标题：Git commit 钩子提交规范校验
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.x06jfh.asia/arts/696970.Doc

原标题：golang 项目环境变量加载方案
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.x06jfh.asia/arts/045421.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.x06jfh.asia/arts/721925.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.x06jfh.asia/arts/479079.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.x06jfh.asia/arts/052011.Doc

原标题：golang 分布式锁防死锁处理
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.x06jfh.asia/arts/302214.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.x06jfh.asia/arts/331720.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.x06jfh.asia/arts/822422.Doc

原标题：实践：灰度流量切分简易实现方案
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.x06jfh.asia/arts/459692.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.x06jfh.asia/arts/296343.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.x06jfh.asia/arts/612607.Doc

原标题：golang kafka 死信队列业务落地
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.x06jfh.asia/arts/085076.Doc

原标题：golang k8s liveness readiness 探针
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.x06jfh.asia/arts/668055.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.x06jfh.asia/arts/758005.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.x06jfh.asia/arts/660295.Doc

原标题：golang etcd watch 监听配置变更
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.x06jfh.asia/arts/145058.Doc

原标题：上传接口跨域配置特殊适配
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.x06jfh.asia/arts/532721.Doc

原标题：MySQL 慢查询索引优化实战
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.x06jfh.asia/arts/539797.Doc

原标题：内存溢出问题现象识别排查
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.x06jfh.asia/arts/452839.Doc

原标题：golang kafka 批量发送消费优化
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.x06jfh.asia/arts/962416.Doc

原标题：主干开发团队代码合并策略
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.x06jfh.asia/arts/829423.Doc

原标题：Cookie Session 会话状态管理
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.x06jfh.asia/arts/051802.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.x06jfh.asia/arts/685097.Doc

原标题：网关超时时间调优后端等待
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.x06jfh.asia/arts/504384.Doc

原标题：golang gitlab runner 部署与注册实操
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.x06jfh.asia/arts/523818.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.x06jfh.asia/arts/224935.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.x06jfh.asia/arts/523577.Doc

原标题：快速入门异步编程基础模型
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.x06jfh.asia/arts/578680.Doc

原标题：golang 速率限制令牌桶实现
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.x06jfh.asia/arts/309820.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.x06jfh.asia/arts/578020.Doc

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.x06jfh.asia/arts/310941.Doc

原标题：部署实践：数据库迁移脚本版本管理实践
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.x06jfh.asia/arts/910627.Doc

原标题：golang traceId spanId 传递方案
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.x06jfh.asia/arts/625845.Doc

原标题：golang docker 容器资源限制设置
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.x06jfh.asia/arts/748806.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.x06jfh.asia/arts/383201.Doc

原标题：Shell 运维脚本服务器效率提升
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.x06jfh.asia/arts/608060.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.x06jfh.asia/arts/309616.Doc

原标题：golang redis stream 消息队列实践
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.x06jfh.asia/arts/129898.Doc

原标题：多操作系统开发兼容处理
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.x06jfh.asia/arts/836081.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.x06jfh.asia/arts/114343.Doc

三、实战开发｜Practice
原标题：golang 系统设计分表分页排序业务实现难点
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.x06jfh.asia/arts/848839.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.x06jfh.asia/arts/975927.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.x06jfh.asia/arts/081864.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.x06jfh.asia/arts/274468.Doc

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.x06jfh.asia/arts/008008.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.x06jfh.asia/arts/731065.Doc

原标题：golang html 模板渲染简单示例
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.x06jfh.asia/arts/077335.Doc

原标题：Git commit 钩子提交规范校验
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.x06jfh.asia/arts/605389.Doc

原标题：项目脚手架模板生成工具
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.x06jfh.asia/arts/003653.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.x06jfh.asia/arts/424393.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://wiki.x06jfh.asia/arts/917957.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.x06jfh.asia/arts/416734.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.x06jfh.asia/arts/245699.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.x06jfh.asia/arts/677336.Doc

原标题：内存溢出问题现象识别排查
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.x06jfh.asia/arts/824522.Doc

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.x06jfh.asia/arts/534868.Doc

原标题：golang prometheus histogram 指标
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.x06jfh.asia/arts/183614.Doc

原标题：ORM 框架数据库增删改查实操
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://wiki.x06jfh.asia/arts/468227.Doc

原标题：项目目录结构规范化最佳实践
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.x06jfh.asia/arts/418486.Doc

原标题：golang websocket 消息广播实现
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.x06jfh.asia/arts/984111.Doc

原标题：前端打包分包加载提速方案
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.x06jfh.asia/arts/811360.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.x06jfh.asia/arts/206892.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.x06jfh.asia/arts/872084.Doc

原标题：后端分页查询逻辑代码实现
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.x06jfh.asia/arts/414789.Doc

原标题：golang es 聚合统计查询实现
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.x06jfh.asia/arts/447644.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.x06jfh.asia/arts/225698.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.x06jfh.asia/arts/351244.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.x06jfh.asia/arts/967897.Doc

原标题：前端虚拟列表大数据渲染优化
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://wiki.x06jfh.asia/arts/111819.Doc

原标题：golang context 上下文传参讲解
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.x06jfh.asia/arts/522166.Doc

原标题：golang mysql innodb 事务隔离级别
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.x06jfh.asia/arts/402051.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.x06jfh.asia/arts/968316.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.x06jfh.asia/arts/749530.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.x06jfh.asia/arts/227148.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.x06jfh.asia/arts/011235.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.x06jfh.asia/arts/417526.Doc

原标题：golang 系统设计基准测试 benchmark 编写
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.x06jfh.asia/arts/674547.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.x06jfh.asia/arts/609054.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.x06jfh.asia/arts/311029.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.x06jfh.asia/arts/881022.Doc

四、架构设计｜Architecture
原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.x06jfh.asia/arts/448804.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.x06jfh.asia/arts/647764.Doc

原标题：前端虚拟列表大数据渲染优化
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.x06jfh.asia/arts/034484.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.x06jfh.asia/arts/583067.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.x06jfh.asia/arts/824583.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.x06jfh.asia/arts/302006.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.x06jfh.asia/arts/274445.Doc

原标题：数据库索引重建提升查询速度
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.x06jfh.asia/arts/391813.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.x06jfh.asia/arts/591107.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.x06jfh.asia/arts/223366.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.x06jfh.asia/arts/636105.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.x06jfh.asia/arts/707211.Doc

原标题：golang websocket 消息广播实现
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.x06jfh.asia/arts/841317.Doc

原标题：golang 简单爬虫请求防封禁
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.x06jfh.asia/arts/447510.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.x06jfh.asia/arts/708506.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.x06jfh.asia/arts/457111.Doc

原标题：golang minio 预签名 url 临时访问
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.x06jfh.asia/arts/867365.Doc

原标题：nodejs 日志轮转生产环境配置
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.x06jfh.asia/arts/568023.Doc

?
