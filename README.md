# qvs
qvs是一个分布式的内存型kv存储库，实现是去中心化的，预计完整实现在12月末

实现列表:

* 包含lru的内存淘汰机制(已实现，并且带有时间过期的功能)
* 租约机制
* 强一致的数据同步备份
* 定期的健康检查
* 消息通知订阅
