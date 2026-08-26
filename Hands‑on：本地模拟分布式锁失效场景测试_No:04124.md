最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.ku2mxy.asia/blog/380775.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.ku2mxy.asia/blog/421855.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.ku2mxy.asia/blog/022151.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://book.ku2mxy.asia/blog/930094.Doc

原标题：文件句柄上限调整上传随机失败
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.ku2mxy.asia/blog/498442.Doc

原标题：golang 时间时区处理避坑指南
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.ku2mxy.asia/blog/355532.Doc

原标题：nodejs 消息队列消费服务开发
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://book.ku2mxy.asia/blog/134912.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.ku2mxy.asia/blog/916266.Doc

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.ku2mxy.asia/blog/014852.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.ku2mxy.asia/blog/056890.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.ku2mxy.asia/blog/730362.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.ku2mxy.asia/blog/976635.Doc

原标题：站内邮件消息通知功能开发
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.ku2mxy.asia/blog/028247.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.ku2mxy.asia/blog/863320.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.ku2mxy.asia/blog/434458.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://book.ku2mxy.asia/blog/432662.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://book.ku2mxy.asia/blog/507016.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://book.ku2mxy.asia/blog/245739.Doc

原标题：坑点：gitpull冲突处理不当造成代码丢失
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.ku2mxy.asia/blog/996478.Doc

原标题：程序预加载加快服务启动速度
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.ku2mxy.asia/blog/575480.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.ku2mxy.asia/blog/673030.Doc

原标题：Shell 运维脚本服务器效率提升
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.ku2mxy.asia/blog/489884.Doc

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.ku2mxy.asia/blog/759876.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.ku2mxy.asia/blog/154417.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.ku2mxy.asia/blog/022211.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.ku2mxy.asia/blog/415252.Doc

原标题：快速入门对象存储基础使用场景
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.ku2mxy.asia/blog/561583.Doc

原标题：包管理器依赖缓存清理
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://book.ku2mxy.asia/blog/963580.Doc

原标题：golang docker 部署 redis 配置要点
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.ku2mxy.asia/blog/784360.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.ku2mxy.asia/blog/905565.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.ku2mxy.asia/blog/041706.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://book.ku2mxy.asia/blog/292525.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.ku2mxy.asia/blog/269095.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.ku2mxy.asia/blog/339656.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.ku2mxy.asia/blog/233209.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.ku2mxy.asia/blog/247603.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.ku2mxy.asia/blog/143958.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.ku2mxy.asia/blog/207007.Doc

原标题：Shell 运维脚本服务器效率提升
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.ku2mxy.asia/blog/823295.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.ku2mxy.asia/blog/492296.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计故障定位排查通用步骤方法论
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.ku2mxy.asia/blog/821711.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.ku2mxy.asia/blog/313851.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.ku2mxy.asia/blog/882541.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.ku2mxy.asia/blog/072113.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.ku2mxy.asia/blog/614148.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.ku2mxy.asia/blog/370614.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.ku2mxy.asia/blog/122177.Doc

原标题：golang 分库分表简单路由实现
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.ku2mxy.asia/blog/488088.Doc

原标题：golang kafka 死信队列业务落地
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.ku2mxy.asia/blog/303403.Doc

原标题：golang 速率限制令牌桶实现
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.ku2mxy.asia/blog/063657.Doc

原标题：浮点计算精度错误处理方案
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.ku2mxy.asia/blog/509965.Doc

原标题：文件句柄上限调整上传随机失败
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.ku2mxy.asia/blog/943726.Doc

原标题：golang redis lua 脚本原子操作
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.ku2mxy.asia/blog/852051.Doc

原标题：golang redis 热点 key 业务规避
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.ku2mxy.asia/blog/420165.Doc

原标题：新手参与开源社区贡献指南
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.ku2mxy.asia/blog/906846.Doc

原标题：前端下载导出文件功能实现
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://book.ku2mxy.asia/blog/676183.Doc

原标题：安全组端口开放网络访问
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.ku2mxy.asia/blog/014720.Doc

原标题：零基础理解版本控制核心概念与工作流
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.ku2mxy.asia/blog/351087.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://book.ku2mxy.asia/blog/339244.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.ku2mxy.asia/blog/762052.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.ku2mxy.asia/blog/662233.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.ku2mxy.asia/blog/248579.Doc

原标题：golang redis 发布订阅简单示例
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.ku2mxy.asia/blog/667907.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.ku2mxy.asia/blog/389988.Doc

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.ku2mxy.asia/blog/400697.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://book.ku2mxy.asia/blog/183051.Doc

原标题：Docker 容器入门镜像实操教程
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.ku2mxy.asia/blog/184488.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.ku2mxy.asia/blog/834873.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.ku2mxy.asia/blog/596336.Doc

原标题：API 接口调试与异常处理实战
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.ku2mxy.asia/blog/679792.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.ku2mxy.asia/blog/711413.Doc

原标题：网关集成鉴权限流日志一体化
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.ku2mxy.asia/blog/684266.Doc

原标题：golang k8s helm chart 简单编写
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.ku2mxy.asia/blog/200629.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://book.ku2mxy.asia/blog/537604.Doc

原标题：golang consul 健康检查服务注册
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.ku2mxy.asia/blog/310764.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.ku2mxy.asia/blog/137700.Doc

原标题：golang 系统设计分布式配置中心思路
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.ku2mxy.asia/blog/174995.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.ku2mxy.asia/blog/721608.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.ku2mxy.asia/blog/781848.Doc

原标题：golang redis lua 脚本原子操作
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.ku2mxy.asia/blog/166185.Doc

三、实战开发｜Practice
原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.ku2mxy.asia/blog/041303.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.ku2mxy.asia/blog/970993.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.ku2mxy.asia/blog/818958.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://book.ku2mxy.asia/blog/230221.Doc

原标题：多线程线程安全脏数据规避
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.ku2mxy.asia/blog/124335.Doc

原标题：定时任务重复执行分布式锁
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://book.ku2mxy.asia/blog/270317.Doc

原标题：数值 key 浮点匹配异常规避
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.ku2mxy.asia/blog/451481.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.ku2mxy.asia/blog/402553.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.ku2mxy.asia/blog/028659.Doc

原标题：golang 大文件 http 下载服务
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.ku2mxy.asia/blog/430659.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://book.ku2mxy.asia/blog/385117.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.ku2mxy.asia/blog/378133.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.ku2mxy.asia/blog/230137.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.ku2mxy.asia/blog/337766.Doc

原标题：golang redis 批量 pipeline 实践
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.ku2mxy.asia/blog/503344.Doc

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.ku2mxy.asia/blog/963610.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.ku2mxy.asia/blog/967878.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.ku2mxy.asia/blog/504930.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.ku2mxy.asia/blog/909509.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.ku2mxy.asia/blog/164918.Doc

原标题：入门实践：使用模板快速生成项目脚手架
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.ku2mxy.asia/blog/623292.Doc

原标题：不必要字符转义关闭业务异常
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://book.ku2mxy.asia/blog/562360.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.ku2mxy.asia/blog/570309.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.ku2mxy.asia/blog/081942.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.ku2mxy.asia/blog/428572.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.ku2mxy.asia/blog/498560.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.ku2mxy.asia/blog/235894.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://book.ku2mxy.asia/blog/932876.Doc

原标题：零基础理解前后端简单交互流程
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.ku2mxy.asia/blog/486245.Doc

原标题：时间同步修复令牌提前过期
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.ku2mxy.asia/blog/714137.Doc

原标题：golang redis 集群 hash 槽讲解
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.ku2mxy.asia/blog/732876.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.ku2mxy.asia/blog/411062.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.ku2mxy.asia/blog/539888.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.ku2mxy.asia/blog/448451.Doc

原标题：CI 构建缓存加速编译速度
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.ku2mxy.asia/blog/758777.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.ku2mxy.asia/blog/565866.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.ku2mxy.asia/blog/786624.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://book.ku2mxy.asia/blog/577467.Doc

原标题：CORS 跨域问题多种解决方案
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.ku2mxy.asia/blog/195633.Doc

原标题：golang 多协程任务池并发控制
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.ku2mxy.asia/blog/892247.Doc

四、架构设计｜Architecture
原标题：开发记录：文件锁实现多进程互斥实践
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.ku2mxy.asia/blog/892057.Doc

原标题：golang 项目 makefile 脚本编写
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.ku2mxy.asia/blog/019525.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.ku2mxy.asia/blog/963897.Doc

原标题：上传接口跨域配置特殊适配
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.ku2mxy.asia/blog/167245.Doc

原标题：golang 内存缓存简单实现方案
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.ku2mxy.asia/blog/227070.Doc

原标题：项目脚手架模板生成工具
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.ku2mxy.asia/blog/237730.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.ku2mxy.asia/blog/640000.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.ku2mxy.asia/blog/087848.Doc

原标题：ORM 框架数据库增删改查实操
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.ku2mxy.asia/blog/727905.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.ku2mxy.asia/blog/733787.Doc

原标题：golang 信号捕获程序退出处理
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.ku2mxy.asia/blog/172118.Doc

原标题：golang 分库分表简单路由实现
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.ku2mxy.asia/blog/369555.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://book.ku2mxy.asia/blog/684704.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.ku2mxy.asia/blog/675877.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.ku2mxy.asia/blog/429025.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.ku2mxy.asia/blog/303555.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.ku2mxy.asia/blog/159281.Doc

原标题：golang mysql 避免 select * 查询
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.ku2mxy.asia/blog/492608.Doc

?
