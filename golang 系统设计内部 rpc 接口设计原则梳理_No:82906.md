最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://gemssensors.com.cn/Article/details/901554.sHtML

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://gemssensors.com.cn/Article/details/869646.sHtML

原标题：设计思考：消息队列重复消费架构层防御手段
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://gemssensors.com.cn/Article/details/201267.sHtML

原标题：记一次日志切割脚本错误直接清空业务日志
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://gemssensors.com.cn/Article/details/644452.sHtML

原标题：golang rate‑limiter 限流组件
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://gemssensors.com.cn/Article/details/458441.sHtML

原标题：express 请求参数校验处理
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://gemssensors.com.cn/Article/details/311233.sHtML

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://gemssensors.com.cn/Article/details/836335.sHtML

原标题：实战：Docker资源监控查看容器状态实操
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://gemssensors.com.cn/Article/details/687188.sHtML

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://gemssensors.com.cn/Article/details/185372.sHtML

原标题：golang redis zset 延时队列实现
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://gemssensors.com.cn/Article/details/467228.sHtML

原标题：golang redis 限流几种实现方案
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://gemssensors.com.cn/Article/details/548774.sHtML

原标题：容器内存扩容 OOM 被杀死修复
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://gemssensors.com.cn/Article/details/311060.sHtML

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://gemssensors.com.cn/Article/details/760689.sHtML

原标题：golang mysql 批量导入数据实操
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://gemssensors.com.cn/Article/details/578740.sHtML

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://gemssensors.com.cn/Article/details/074422.sHtML

原标题：golang 系统设计数据库基准压测简单思路
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://gemssensors.com.cn/Article/details/196844.sHtML

原标题：优化实践：读写分离分担主库查询压力
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://gemssensors.com.cn/Article/details/932829.sHtML

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://gemssensors.com.cn/Article/details/631969.sHtML

原标题：golang redis 分布式锁 redisson 思路
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://gemssensors.com.cn/Article/details/755425.sHtML

原标题：从零学习简单分布式ID生成思路
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://gemssensors.com.cn/Article/details/120959.sHtML

原标题：golang alertmanager 钉钉告警推送
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://gemssensors.com.cn/Article/details/978274.sHtML

原标题：golang kafka 消息顺序性保证方案
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://gemssensors.com.cn/Article/details/346200.sHtML

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://gemssensors.com.cn/Article/details/673325.sHtML

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://gemssensors.com.cn/Article/details/379521.sHtML

原标题：项目实践：幂等表实现接口幂等业务实践
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://gemssensors.com.cn/Article/details/087877.sHtML

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://gemssensors.com.cn/Article/details/974084.sHtML

原标题：线上故障：消息队列重复消费业务处理异常
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://gemssensors.com.cn/Article/details/803233.sHtML

原标题：前端国际化多语言方案落地
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://gemssensors.com.cn/Article/details/970231.sHtML

原标题：golang 链路追踪简易实现方案
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://gemssensors.com.cn/Article/details/750212.sHtML

原标题：golang 系统设计配置敏感信息加密存储
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://gemssensors.com.cn/Article/details/899693.sHtML

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://gemssensors.com.cn/Article/details/056529.sHtML

原标题：看懂报错日志快速定位问题
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://gemssensors.com.cn/Article/details/427257.sHtML

原标题：排错：前端缓存304异常更新不及时
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://gemssensors.com.cn/Article/details/488766.sHtML

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://gemssensors.com.cn/Article/details/550201.sHtML

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://gemssensors.com.cn/Article/details/382940.sHtML

原标题：golang go test 覆盖率统计实操
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://gemssensors.com.cn/Article/details/003999.sHtML

原标题：Redis 分布式锁高并发安全实现
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://gemssensors.com.cn/Article/details/021718.sHtML

原标题：安全实践：备份文件访问权限安全管控
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://gemssensors.com.cn/Article/details/486626.sHtML

原标题：端口占用释放资源重启服务
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://gemssensors.com.cn/Article/details/577614.sHtML

原标题：从零编写简易 CLI 命令行工具
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://gemssensors.com.cn/Article/details/071333.sHtML


二、踩坑排错｜Troubleshooting
原标题：零基础理解跨域问题产生原因与基础方案
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://gemssensors.com.cn/Article/details/719287.sHtML

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://gemssensors.com.cn/Article/details/163585.sHtML

原标题：golang github actions 缓存依赖提速
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://gemssensors.com.cn/Article/details/896463.sHtML

原标题：入门实践：Git分支创建切换合并完整演示
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://gemssensors.com.cn/Article/details/218367.sHtML

原标题：golang 系统设计防重复提交实现
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://gemssensors.com.cn/Article/details/156888.sHtML

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://gemssensors.com.cn/Article/details/298703.sHtML

原标题：零基础理解读写分离基础思想
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://gemssensors.com.cn/Article/details/282028.sHtML

原标题：Practice：实现接口mock动态返回不同响应
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://gemssensors.com.cn/Article/details/081585.sHtML

原标题：浏览器缓存强制刷新方案
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://gemssensors.com.cn/Article/details/954658.sHtML

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://gemssensors.com.cn/Article/details/396704.sHtML

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://gemssensors.com.cn/Article/details/175065.sHtML

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://gemssensors.com.cn/Article/details/147533.sHtML

原标题：golang websocket 服务端开发
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://gemssensors.com.cn/Article/details/639926.sHtML

原标题：开源实践：开源项目如何写好PullRequest
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://gemssensors.com.cn/Article/details/275000.sHtML

原标题：golang 系统设计灰度发布实现思路
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://gemssensors.com.cn/Article/details/677581.sHtML

原标题：golang 优雅处理 http 超时设置
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://gemssensors.com.cn/Article/details/042956.sHtML

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://gemssensors.com.cn/Article/details/934407.sHtML

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://gemssensors.com.cn/Article/details/196955.sHtML

原标题：golang 系统设计 csrf 接口防护实现
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://gemssensors.com.cn/Article/details/827622.sHtML

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://gemssensors.com.cn/Article/details/661373.sHtML

原标题：GitHub 项目提交推送完整流程讲解
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://gemssensors.com.cn/Article/details/123771.sHtML

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://gemssensors.com.cn/Article/details/567662.sHtML

原标题：新手快速上手 Git 版本控制实操指南
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://gemssensors.com.cn/Article/details/116109.sHtML

原标题：golang 工具函数库封装思路
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://gemssensors.com.cn/Article/details/884111.sHtML

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://gemssensors.com.cn/Article/details/432959.sHtML

原标题：golang 系统设计埋点数据上报方案
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://gemssensors.com.cn/Article/details/374636.sHtML

原标题：Performance：避免全表扫描索引失效场景汇总
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://gemssensors.com.cn/Article/details/595598.sHtML

原标题：实战：基于内存实现简单消息广播组件
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://gemssensors.com.cn/Article/details/456964.sHtML

原标题：golang gin 框架接口开发实战
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://gemssensors.com.cn/Article/details/300261.sHtML

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://gemssensors.com.cn/Article/details/685852.sHtML

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://gemssensors.com.cn/Article/details/676096.sHtML

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://gemssensors.com.cn/Article/details/977772.sHtML

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://gemssensors.com.cn/Article/details/564347.sHtML

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://gemssensors.com.cn/Article/details/636851.sHtML

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://gemssensors.com.cn/Article/details/556052.sHtML

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://gemssensors.com.cn/Article/details/772523.sHtML

原标题：Redis 内存淘汰策略数据防丢失
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://gemssensors.com.cn/Article/details/114775.sHtML

原标题：golang docker 容器资源限制设置
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://gemssensors.com.cn/Article/details/799540.sHtML

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://gemssensors.com.cn/Article/details/208382.sHtML

原标题：快速入门YAML配置文件语法与示例
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://gemssensors.com.cn/Article/details/423079.sHtML

三、实战开发｜Practice
原标题：golang 协程泄露问题排查方法
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://gemssensors.com.cn/Article/details/498113.sHtML

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://gemssensors.com.cn/Article/details/525175.sHtML

原标题：golang 系统设计定时任务执行超时中断防护
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://gemssensors.com.cn/Article/details/260476.sHtML

原标题：项目语义化版本号规范管理
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://gemssensors.com.cn/Article/details/750393.sHtML

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://gemssensors.com.cn/Article/details/412845.sHtML

原标题：golang 系统设计热点数据缓存处理
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://gemssensors.com.cn/Article/details/532150.sHtML

原标题：golang nginx 反向代理 go 服务配置
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://gemssensors.com.cn/Article/details/601864.sHtML

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://gemssensors.com.cn/Article/details/020768.sHtML

原标题：golang 分布式锁 redis 实现
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://gemssensors.com.cn/Article/details/452411.sHtML

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://gemssensors.com.cn/Article/details/526556.sHtML

原标题：接口请求重试容错机制实现
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://gemssensors.com.cn/Article/details/753931.sHtML

原标题：Docker 多阶段构建镜像瘦身
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://gemssensors.com.cn/Article/details/060284.sHtML

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://gemssensors.com.cn/Article/details/541390.sHtML

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://gemssensors.com.cn/Article/details/374408.sHtML

原标题：网关超时时间调优后端等待
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://gemssensors.com.cn/Article/details/983527.sHtML

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://gemssensors.com.cn/Article/details/896601.sHtML

原标题：golang ip 限流黑名单实现方案
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://gemssensors.com.cn/Article/details/530446.sHtML

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://gemssensors.com.cn/Article/details/866887.sHtML

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://gemssensors.com.cn/Article/details/596105.sHtML

原标题：eslint prettier 代码规范落地
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://gemssensors.com.cn/Article/details/114650.sHtML

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://gemssensors.com.cn/Article/details/788024.sHtML

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://gemssensors.com.cn/Article/details/728668.sHtML

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://gemssensors.com.cn/Article/details/084661.sHtML

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://gemssensors.com.cn/Article/details/356375.sHtML

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://gemssensors.com.cn/Article/details/593017.sHtML

原标题：Cookie 跨环境登录配置调整
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://gemssensors.com.cn/Article/details/967008.sHtML

原标题：golang 系统设计用户签到统计方案
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://gemssensors.com.cn/Article/details/318781.sHtML

原标题：Performance：后端接口性能优化完整分析流程
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://gemssensors.com.cn/Article/details/264237.sHtML

原标题：golang 系统设计降级策略开关配置方案
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://gemssensors.com.cn/Article/details/015666.sHtML

原标题：golang 优雅处理系统信号 SIGINT
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://gemssensors.com.cn/Article/details/997366.sHtML

原标题：golang prometheus 告警规则编写
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://gemssensors.com.cn/Article/details/780715.sHtML

原标题：安全实践：防止重放攻击接口签名方案
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://gemssensors.com.cn/Article/details/667641.sHtML

原标题：架构笔记：业务操作审计日志系统架构设计
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://gemssensors.com.cn/Article/details/680644.sHtML

原标题：service‑worker 离线缓存实践
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://gemssensors.com.cn/Article/details/165593.sHtML

原标题：多版本开发环境共存配置
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://gemssensors.com.cn/Article/details/618076.sHtML

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://gemssensors.com.cn/Article/details/756998.sHtML

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://gemssensors.com.cn/Article/details/719417.sHtML

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://gemssensors.com.cn/Article/details/934762.sHtML

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://gemssensors.com.cn/Article/details/961666.sHtML

原标题：一次数据库死锁现场分析与解决方案记录
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://gemssensors.com.cn/Article/details/331099.sHtML

四、架构设计｜Architecture
原标题：Debug：Websocket频繁断开重连根因分析
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://gemssensors.com.cn/Article/details/642044.sHtML

原标题：golang 系统设计大流量削峰处理方案
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://gemssensors.com.cn/Article/details/126760.sHtML

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://gemssensors.com.cn/Article/details/530533.sHtML

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://gemssensors.com.cn/Article/details/901396.sHtML

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://gemssensors.com.cn/Article/details/741360.sHtML

原标题：零基础理解幂等性基础概念与场景
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://gemssensors.com.cn/Article/details/837287.sHtML

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://gemssensors.com.cn/Article/details/776186.sHtML

原标题：进程线程并发基础概念讲解
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://gemssensors.com.cn/Article/details/277350.sHtML

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://gemssensors.com.cn/Article/details/489539.sHtML

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://gemssensors.com.cn/Article/details/331076.sHtML

原标题：快速入门异步编程基础模型
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://gemssensors.com.cn/Article/details/048400.sHtML

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://gemssensors.com.cn/Article/details/863288.sHtML

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://gemssensors.com.cn/Article/details/154134.sHtML

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://gemssensors.com.cn/Article/details/637717.sHtML

原标题：golang 系统设计压测指标确定与分析
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://gemssensors.com.cn/Article/details/500363.sHtML

原标题：golang 系统设计日志规范结构化日志落地
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://gemssensors.com.cn/Article/details/078589.sHtML

原标题：Practice：实现请求body重复读取中间件实践
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://gemssensors.com.cn/Article/details/344799.sHtML

原标题：golang redis 过期策略内存淘汰
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://gemssensors.com.cn/Article/details/593559.sHtML

?
