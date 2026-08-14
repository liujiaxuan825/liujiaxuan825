# 分布式锁实践

## Redis实现
- SETNX + 过期时间
- Lua脚本保证原子性
- Redisson框架

## 注意事项
- 锁粒度
- 可重入
- 死锁预防
