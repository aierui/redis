# 文件结构

| 源代码 | 核心功能 | 备注 |
|--|--|--|
|adlist.c | 双向链表的实现 |   |
|ae.c | 事件驱动基础库 | |
|ae_epoll.c | Linux epoll(2)  | |
|ae_evport.c | 事件端口 | |
|ae_kqueue.c | Kqueue(2) | |
|ae_select.c | Select() | |
|anet.c | TCP 套接字 | |
|aof.c | AOF持久化 | |
|bio.c | 后台 IO 服务| |
|bitops.c | 位操作 | |
|blocked.c | 阻塞操作 | |
|childinfo.c | RDB、AOF 父子进程交互 | |
|cluster.c | 集群实现 | |
|config.c | 配置文件解析 | |
|crc16.c | CRC16 | |
|crc64.c | CRC64 | |
|db.c | 数据库底层实现 | |
|debug.c | 调试 | |
|defrag.c | 内存碎片整理实现 | |
|dict.c | 字典实现 | |
|endianconv.c | 尾数转换 | |
|evict.c | LRU 驱逐策略 | |
|expire.c | 具有固定生存时间的键 | |
|geo.c | Geo  | |
|geohash.c | Geo 哈希算法 | |
|geohash_helper.c |  Geo 哈希算法 | |
|hyperloglog.c | HyperLogLog 实现 | |
|intset.c | 整数集合 | |
|latency.c | 延迟监视器 | |
|lazyfree.c | 内存释放 | |
|listpack.c | 字符串序列化列表 | |
|localtime.c | 时区和夏令时 | |
|lolwut.c | LOLWUT 命令 | |
|lolwut5.c | LOLWUT 命令 | |
|lzf_c.c | Lzf 压缩 | |
|lzf_d.c | Lzf 解压 | |
|memtest.c | 内存测试 | |
|module.c | 系统内部的模块 | |
|multi.c | 批量执行 | |
|networking.c | 网络连接 | |
|notify.c | Pub/Sub | |
|object.c | Redis 对象实现 | |
|pqsort.c | Qsort 实现 | |
|pubsub.c | Pubsub API | |
|quicklist.c | 快速链表 | |
|rand.c | drand48() 实现 | |
|rax.c | 基数树实现 | |
|rdb.c | RDB持久化 | |
|redis-benchmark.c | 压测工具 | |
|redis-check-aof.c | AOF文件检测 | |
|redis-check-rdb.c | RDB文件检测 | |
|redis-cli.c | 客户端实现 | |
|release.c | Redis版本 | |
|replication.c | 主从复制 | |
|rio.c | 流式IO | |
|scripting.c | Lua 脚本 | |
|sds.c | 动态字符串实现 | |
|sentinel.c | Redis 哨兵实现 | |
|server.c | Redis-Server 实现 | |
|setproctitle.c | 设置进程标题 | |
|sha1.c | sha1 实现 | |
|siphash.c | SipHash 实现 | |
|slowlog.c | 满日志 | |
|sort.c | 排序命令实现 | |
|sparkline.c | ASCII 图形 | |
|syncio.c | 同步IO | |
|t_hash.c | Hash 命令 | |
|t_list.c | List 命令 | |
|t_set.c | Set 命令 | |
|t_stream.c | Stream 命令 | |
|t_string.c | String 命令 | |
|t_zset.c | Zset 命令 | |
|util.c | 工具函数 | |
|ziplist.c | 压缩列表 | |
|zipmap.c | 字符串映射 | |
|zmalloc.c | 内存分配 | |