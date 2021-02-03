---
toc_priority: 32
toc_title: Atomic
---

# 原子引擎 {#atomic}
这个引擎支持非阻塞式的`DROP` 和 `RENAME TABLE`和`EXCHANGE TABLES t1 AND t2`的查询。数据库默认引擎就是原子引擎

## 创建一个数据库 {#creating-a-database}
```sql
CREATE DATABASE test ENGINE = Atomic;
```

[Original article](https://clickhouse.tech/docs/en/engines/database_engines/atomic/) <!--hide-->
