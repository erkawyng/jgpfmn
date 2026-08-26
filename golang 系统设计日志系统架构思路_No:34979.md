最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计日志系统架构思路
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://book.ztcz81.asia/blog/020945.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.ztcz81.asia/blog/487369.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.ztcz81.asia/blog/612777.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.ztcz81.asia/blog/608643.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.ztcz81.asia/blog/292792.Doc

原标题：文件锁正确使用避免死锁
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.ztcz81.asia/blog/319671.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.ztcz81.asia/blog/511605.Doc

原标题：golang redis 过期 key 监听业务
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.ztcz81.asia/blog/205340.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.ztcz81.asia/blog/723475.Doc

原标题：golang 集成测试启动测试数据库
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.ztcz81.asia/blog/724011.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.ztcz81.asia/blog/041407.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.ztcz81.asia/blog/308728.Doc

原标题：项目构建脚本编译打包解析
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.ztcz81.asia/blog/513851.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.ztcz81.asia/blog/967085.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.ztcz81.asia/blog/729280.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.ztcz81.asia/blog/753960.Doc

原标题：包管理器依赖冲突解决方案
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://book.ztcz81.asia/blog/380652.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.ztcz81.asia/blog/321075.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.ztcz81.asia/blog/279884.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.ztcz81.asia/blog/204250.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.ztcz81.asia/blog/314124.Doc

原标题：golang 系统设计故障演练简单思路
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.ztcz81.asia/blog/604999.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.ztcz81.asia/blog/559620.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.ztcz81.asia/blog/491421.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.ztcz81.asia/blog/427555.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.ztcz81.asia/blog/151543.Doc

原标题：golang prometheus 告警规则编写
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.ztcz81.asia/blog/423348.Doc

原标题：golang mysql 连接泄漏检测方法
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.ztcz81.asia/blog/765484.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.ztcz81.asia/blog/291797.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.ztcz81.asia/blog/267074.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://book.ztcz81.asia/blog/107754.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://book.ztcz81.asia/blog/479478.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.ztcz81.asia/blog/530328.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.ztcz81.asia/blog/959018.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.ztcz81.asia/blog/963082.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.ztcz81.asia/blog/267727.Doc

原标题：golang redis 网络超时参数调优
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.ztcz81.asia/blog/346022.Doc

原标题：pnpm 包管理工具实战避坑指南
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.ztcz81.asia/blog/020199.Doc

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.ztcz81.asia/blog/567825.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.ztcz81.asia/blog/905959.Doc


二、踩坑排错｜Troubleshooting
原标题：5分钟快速搭建个人技术文档站点
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.ztcz81.asia/blog/014435.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.ztcz81.asia/blog/721097.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.ztcz81.asia/blog/225779.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.ztcz81.asia/blog/931966.Doc

原标题：后端分页查询逻辑代码实现
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.ztcz81.asia/blog/972832.Doc

原标题：golang prometheus 指标暴露实现
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.ztcz81.asia/blog/340060.Doc

原标题：golang 系统设计序列化性能选型对比
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://book.ztcz81.asia/blog/828698.Doc

原标题：Hands‑on：简易链路追踪原型开发实践
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.ztcz81.asia/blog/161092.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.ztcz81.asia/blog/274669.Doc

原标题：golang 优雅停机服务关闭实现
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://book.ztcz81.asia/blog/737841.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.ztcz81.asia/blog/571103.Doc

原标题：golang rsa 非对称加密签名验签
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.ztcz81.asia/blog/145123.Doc

原标题：记一次分布式锁失效引发的数据错乱问题
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.ztcz81.asia/blog/860690.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.ztcz81.asia/blog/455540.Doc

原标题：简易网关请求路由过滤模拟
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.ztcz81.asia/blog/986293.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.ztcz81.asia/blog/686179.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.ztcz81.asia/blog/931447.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.ztcz81.asia/blog/230677.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.ztcz81.asia/blog/831160.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.ztcz81.asia/blog/563387.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.ztcz81.asia/blog/011374.Doc

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.ztcz81.asia/blog/633228.Doc

原标题：多环境配置中心灵活切换方案
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.ztcz81.asia/blog/037458.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.ztcz81.asia/blog/613707.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.ztcz81.asia/blog/904959.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.ztcz81.asia/blog/072836.Doc

原标题：git stash 代码暂存切换分支
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.ztcz81.asia/blog/388703.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.ztcz81.asia/blog/384768.Doc

原标题：新手指南：本地多版本环境共存配置
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.ztcz81.asia/blog/154213.Doc

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.ztcz81.asia/blog/266319.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.ztcz81.asia/blog/934335.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.ztcz81.asia/blog/723073.Doc

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.ztcz81.asia/blog/622726.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.ztcz81.asia/blog/205475.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.ztcz81.asia/blog/856406.Doc

原标题：gitignore 文件编写过滤规则
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.ztcz81.asia/blog/718604.Doc

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.ztcz81.asia/blog/187253.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.ztcz81.asia/blog/285748.Doc

原标题：从零搭建本地开发环境完整教程
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.ztcz81.asia/blog/826559.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.ztcz81.asia/blog/752996.Doc

三、实战开发｜Practice
原标题：golang 系统设计缓存过期时间设置原则梳理
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://book.ztcz81.asia/blog/303982.Doc

原标题：golang 单元测试 table‑driven
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.ztcz81.asia/blog/965870.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://book.ztcz81.asia/blog/334878.Doc

原标题：golang gorm 预加载关联查询优化
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.ztcz81.asia/blog/545587.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.ztcz81.asia/blog/189000.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.ztcz81.asia/blog/453756.Doc

原标题：新手教程：本地环境变量配置全流程
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.ztcz81.asia/blog/648165.Doc

原标题：golang redis 缓存穿透解决方案
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://book.ztcz81.asia/blog/522967.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.ztcz81.asia/blog/869402.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.ztcz81.asia/blog/931437.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.ztcz81.asia/blog/292501.Doc

原标题：Spring 事务传播机制配置生效
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.ztcz81.asia/blog/704443.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://book.ztcz81.asia/blog/482736.Doc

原标题：系统字符集统一乱码修复
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://book.ztcz81.asia/blog/606895.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.ztcz81.asia/blog/334338.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.ztcz81.asia/blog/129774.Doc

原标题：golang context 上下文传参讲解
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.ztcz81.asia/blog/993886.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.ztcz81.asia/blog/666399.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.ztcz81.asia/blog/777856.Doc

原标题：golang 系统设计故障演练简单思路
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.ztcz81.asia/blog/642598.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.ztcz81.asia/blog/485679.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://book.ztcz81.asia/blog/282197.Doc

原标题：零基础理解模块化与组件化基础思想
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://book.ztcz81.asia/blog/400258.Doc

原标题：网络读取超时设置连接挂起防护
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.ztcz81.asia/blog/864635.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.ztcz81.asia/blog/571754.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.ztcz81.asia/blog/711170.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://book.ztcz81.asia/blog/059780.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.ztcz81.asia/blog/339116.Doc

原标题：golang es bool 查询条件组合技巧
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://book.ztcz81.asia/blog/023069.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.ztcz81.asia/blog/471181.Doc

原标题：golang kafka 监控指标简单梳理
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.ztcz81.asia/blog/312766.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.ztcz81.asia/blog/889795.Doc

原标题：CI 流水线超时时间延长配置
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.ztcz81.asia/blog/043946.Doc

原标题：golang 系统设计定时任务执行超时中断防护
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.ztcz81.asia/blog/593579.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.ztcz81.asia/blog/603726.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://book.ztcz81.asia/blog/261330.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.ztcz81.asia/blog/788960.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.ztcz81.asia/blog/522716.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.ztcz81.asia/blog/610831.Doc

原标题：批量异步处理系统业务落地
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.ztcz81.asia/blog/454410.Doc

四、架构设计｜Architecture
原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.ztcz81.asia/blog/384545.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.ztcz81.asia/blog/713067.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.ztcz81.asia/blog/018365.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.ztcz81.asia/blog/704053.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.ztcz81.asia/blog/363847.Doc

原标题：golang grafana 面板变量模板制作
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.ztcz81.asia/blog/548082.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.ztcz81.asia/blog/420701.Doc

原标题：golang mysql 连接泄漏检测方法
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.ztcz81.asia/blog/923094.Doc

原标题：极简 API 网关路由转发实现
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.ztcz81.asia/blog/755022.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.ztcz81.asia/blog/522178.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.ztcz81.asia/blog/299064.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.ztcz81.asia/blog/298049.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.ztcz81.asia/blog/567615.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.ztcz81.asia/blog/918599.Doc

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.ztcz81.asia/blog/058440.Doc

原标题：项目构建脚本编译打包解析
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.ztcz81.asia/blog/449906.Doc

原标题：golang 跨域处理中间件编写
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.ztcz81.asia/blog/241586.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.ztcz81.asia/blog/450955.Doc

?
