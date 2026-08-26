最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.pb0hct.asia/arts/214693.Doc

原标题：golang 系统设计分布式配置中心思路
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.pb0hct.asia/arts/122706.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.pb0hct.asia/arts/715199.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.pb0hct.asia/arts/893887.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.pb0hct.asia/arts/266529.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.pb0hct.asia/arts/496316.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.pb0hct.asia/arts/688133.Doc

原标题：golang redis 发布订阅简单示例
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.pb0hct.asia/arts/232404.Doc

原标题：golang k8s helm chart 简单编写
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.pb0hct.asia/arts/353589.Doc

原标题：golang k8s cronjob 定时任务配置
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.pb0hct.asia/arts/575401.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.pb0hct.asia/arts/045254.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://wiki.pb0hct.asia/arts/666483.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.pb0hct.asia/arts/250562.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.pb0hct.asia/arts/414363.Doc

原标题：golang 集成测试启动测试数据库
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.pb0hct.asia/arts/126548.Doc

原标题：Nginx 丢失请求头配置修正
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.pb0hct.asia/arts/362456.Doc

原标题：golang redis 连接池参数最佳值
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.pb0hct.asia/arts/991152.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.pb0hct.asia/arts/964103.Doc

原标题：零基础理解模块化与组件化基础思想
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.pb0hct.asia/arts/512244.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.pb0hct.asia/arts/073503.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.pb0hct.asia/arts/193192.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.pb0hct.asia/arts/381814.Doc

原标题：golang github actions 完整工作流示例
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.pb0hct.asia/arts/774505.Doc

原标题：网络读取超时设置连接挂起防护
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.pb0hct.asia/arts/562683.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://wiki.pb0hct.asia/arts/723622.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.pb0hct.asia/arts/019388.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.pb0hct.asia/arts/074070.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.pb0hct.asia/arts/388027.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.pb0hct.asia/arts/370458.Doc

原标题：git rebase 整理提交历史实操
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.pb0hct.asia/arts/730726.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.pb0hct.asia/arts/163344.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.pb0hct.asia/arts/277765.Doc

原标题：css 变量主题切换方案实现
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.pb0hct.asia/arts/782871.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.pb0hct.asia/arts/136632.Doc

原标题：golang 优雅停机服务关闭实现
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.pb0hct.asia/arts/150173.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.pb0hct.asia/arts/901698.Doc

原标题：异步任务堆积消费能力优化
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.pb0hct.asia/arts/057889.Doc

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.pb0hct.asia/arts/897982.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.pb0hct.asia/arts/783512.Doc

原标题：慢查询分析索引调优数据库实战
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.pb0hct.asia/arts/726899.Doc


二、踩坑排错｜Troubleshooting
原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.pb0hct.asia/arts/643082.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.pb0hct.asia/arts/385695.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.pb0hct.asia/arts/364022.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.pb0hct.asia/arts/704200.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.pb0hct.asia/arts/238437.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/960983.Doc

原标题：golang redis 缓存穿透解决方案
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.pb0hct.asia/arts/523319.Doc

原标题：后端大文件分片上传接口开发
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.pb0hct.asia/arts/796928.Doc

原标题：多环境配置中心灵活切换方案
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.pb0hct.asia/arts/152801.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.pb0hct.asia/arts/775646.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.pb0hct.asia/arts/781586.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.pb0hct.asia/arts/573522.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.pb0hct.asia/arts/537002.Doc

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.pb0hct.asia/arts/148907.Doc

原标题：golang 单元测试 mock http 请求
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.pb0hct.asia/arts/076463.Doc

原标题：新手教程：本地环境变量配置全流程
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.pb0hct.asia/arts/566011.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.pb0hct.asia/arts/264643.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.pb0hct.asia/arts/630178.Doc

原标题：golang ci 流水线漏洞扫描依赖检查
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.pb0hct.asia/arts/819485.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.pb0hct.asia/arts/830953.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.pb0hct.asia/arts/411730.Doc

原标题：golang 接口限流中间件开发
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.pb0hct.asia/arts/274372.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.pb0hct.asia/arts/020218.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.pb0hct.asia/arts/574880.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/850239.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.pb0hct.asia/arts/726793.Doc

原标题：语义化版本依赖管理防错乱
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.pb0hct.asia/arts/499635.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.pb0hct.asia/arts/435667.Doc

原标题：golang k8s rbac 权限控制配置示例
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.pb0hct.asia/arts/680444.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.pb0hct.asia/arts/130963.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://wiki.pb0hct.asia/arts/003063.Doc

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.pb0hct.asia/arts/607817.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.pb0hct.asia/arts/545777.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.pb0hct.asia/arts/950689.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.pb0hct.asia/arts/747393.Doc

原标题：golang gorm 预加载关联查询优化
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.pb0hct.asia/arts/991362.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.pb0hct.asia/arts/527435.Doc

原标题：GitHub 项目提交推送完整流程讲解
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.pb0hct.asia/arts/695923.Doc

原标题：方案设计：统一错误处理架构全链路方案
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.pb0hct.asia/arts/578183.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.pb0hct.asia/arts/036433.Doc

三、实战开发｜Practice
原标题：项目实践：多环境配置管理组件设计与实现
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.pb0hct.asia/arts/191182.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.pb0hct.asia/arts/711405.Doc

原标题：多线程线程安全脏数据规避
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.pb0hct.asia/arts/747842.Doc

原标题：golang 系统设计 README 开源文档模板
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.pb0hct.asia/arts/355992.Doc

原标题：golang 分布式锁防死锁处理
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.pb0hct.asia/arts/791733.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/786851.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.pb0hct.asia/arts/595148.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.pb0hct.asia/arts/236631.Doc

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/743241.Doc

原标题：分布式锁失效问题排查修复
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.pb0hct.asia/arts/980808.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.pb0hct.asia/arts/406184.Doc

原标题：配置与镜像分离防止信息泄露
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.pb0hct.asia/arts/893365.Doc

原标题：golang 优雅处理数据库事务
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.pb0hct.asia/arts/166570.Doc

原标题：新手教程：本地项目初始化gitignore配置
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.pb0hct.asia/arts/960481.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/203701.Doc

原标题：golang kafka 批量发送消费优化
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.pb0hct.asia/arts/597184.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.pb0hct.asia/arts/023958.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.pb0hct.asia/arts/774444.Doc

原标题：新手参与开源社区贡献指南
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.pb0hct.asia/arts/872589.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.pb0hct.asia/arts/655653.Doc

原标题：接口幂等性防重复请求实现
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.pb0hct.asia/arts/799684.Doc

原标题：golang 系统设计故障演练简单思路
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.pb0hct.asia/arts/201327.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.pb0hct.asia/arts/292062.Doc

原标题：入门实战：搭建简易静态网页项目
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.pb0hct.asia/arts/159118.Doc

原标题：OAuth2 第三方登录服务搭建
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.pb0hct.asia/arts/959591.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.pb0hct.asia/arts/209236.Doc

原标题：golang 系统设计限流服务架构讲解
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.pb0hct.asia/arts/193777.Doc

原标题：从零搭建简单的健康检查接口示例
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://wiki.pb0hct.asia/arts/892894.Doc

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.pb0hct.asia/arts/979252.Doc

原标题：代理 HTTPS 证书访问异常处理
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.pb0hct.asia/arts/189076.Doc

原标题：本地数据库开发环境搭建指南
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.pb0hct.asia/arts/901562.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/781244.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.pb0hct.asia/arts/308274.Doc

原标题：golang etcd 配置中心简单使用
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.pb0hct.asia/arts/112389.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.pb0hct.asia/arts/809544.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.pb0hct.asia/arts/995369.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.pb0hct.asia/arts/591937.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.pb0hct.asia/arts/825400.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.pb0hct.asia/arts/535790.Doc

原标题：CI 流水线超时时间延长配置
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.pb0hct.asia/arts/776913.Doc

四、架构设计｜Architecture
原标题：golang 表单文件大小限制配置
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.pb0hct.asia/arts/898548.Doc

原标题：golang 系统设计代码评审 checklist 清单
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.pb0hct.asia/arts/011233.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.pb0hct.asia/arts/136842.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.pb0hct.asia/arts/610108.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.pb0hct.asia/arts/236478.Doc

原标题：新手参与开源社区贡献指南
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.pb0hct.asia/arts/804953.Doc

原标题：golang 单元测试 table‑driven
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.pb0hct.asia/arts/679060.Doc

原标题：操作系统内核版本适配服务
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/013888.Doc

原标题：golang 日志与链路 ID 关联打印
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.pb0hct.asia/arts/212820.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.pb0hct.asia/arts/862020.Doc

原标题：文件批量导入导出功能实现
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.pb0hct.asia/arts/711800.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.pb0hct.asia/arts/027000.Doc

原标题：golang 重试退避机制代码实现
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.pb0hct.asia/arts/914135.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.pb0hct.asia/arts/788028.Doc

原标题：布隆过滤器误判问题修正
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.pb0hct.asia/arts/098500.Doc

原标题：入门实践：简单的请求封装与异常捕获
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.pb0hct.asia/arts/935358.Doc

原标题：Git 子模块更新代码不全修复
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.pb0hct.asia/arts/127813.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.pb0hct.asia/arts/447063.Doc

?
