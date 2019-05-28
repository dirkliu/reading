# Redis深度历险　　
核心原理与应用实践

### 基础与应用　
* 数据结构　　
string, list, hash, set, zset
* 分布式锁　　　
超时问题，可重入性　　
* 延时队列　　
锁冲突处理：1．直接抛出异常；2．sleep；3．延时队列
* 位图　　
位图的基本用法　　
* HyperLogLog 
* 布隆过滤器  
不精确的set结构，存在误判  
布隆过滤器原理:  
无偏hash函数
* 漏斗限流 
* GeoHash
* Scan 

### 原理
* 线程IO模型  
redis是个单线程程序，所有数据都在内存中  
非阻塞IO  
多路复用  
* 通信协议  
resp协议： Redis Serialization Protocol
* 持久化  
保证Redis的数据不会因为故障而丢失。  
快照原理  
多进程  
AOF原理  
fsyn

### 集群

### 拓展　

### 源码　

