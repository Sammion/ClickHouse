---
machine_translated: true
machine_translated_rev: 72537a2d527c63c07aa5d2361a8829f3895cf2bd
toc_folder_title: "\u8868\u51FD\u6570"
toc_priority: 34
toc_title: "\u5BFC\u8A00"
---

# 表函数 {#table-functions}

表函数这里指的是构造表时的方法。

您可以像这样使用表函数:

-   `SELECT` 查询的[FROM](../statements/select/from.md)。

        The method for creating a temporary table that is available only in the current query. The table is deleted when the query finishes.

-   [创建表为\<table_function()\>](../statements/create.md#create-table-query) 查询。

        It's one of the methods of creating a table.

!!! warning "警告"
    如果 [allow_ddl](../../operations/settings/permissions-for-queries.md#settings_allow_ddl) 设置被禁用，你不能使用表函数。

| 功能               | 产品描述                                                                                               |
|--------------------|--------------------------------------------------------------------------------------------------------|
| [文件](file.md)    | 创建一个 [File-engine](../../engines/table-engines/special/file.md)表。                                |
| [合并](merge.md)   | 创建一个 [Merge-engine](../../engines/table-engines/special/merge.md)-发动机表。                               |
| [数字](numbers.md) | 创建一个整数填充列的表。                                                                       |
| [远程](remote.md)  | 允许您访问远程服务器，而无需创建 [Distributed-engine](../../engines/table-engines/special/distributed.md)表。 |
| [url](url.md)      | 创建一个 [Url-engine](../../engines/table-engines/special/url.md)-发动机表。                                  |
| [mysql](mysql.md)  | 创建一个 [MySQL-engine](../../engines/table-engines/integrations/mysql.md)-表。                         |
| [jdbc](jdbc.md)    | 创建一个 [JDBC-engine](../../engines/table-engines/integrations/jdbc.md)-表。                           |
| [odbc](odbc.md)    | 创建一个 [ODBC-engine](../../engines/table-engines/integrations/odbc.md)-表。                           |
| [hdfs](hdfs.md)    | 创建一个 [HDFS-engine](../../engines/table-engines/integrations/hdfs.md)-表。                           |

[原始文章](https://clickhouse.tech/docs/en/query_language/table_functions/) <!--hide-->
