# 查询扫描策略
在SQLite中对表的查询扫描策略有如下几种方式：
1.	全表扫描，一般在不使用Where语句时使用；
2.	基于索引扫描，在查询的表有索引并且Where语句中的条件可以使用该索引时使用；
3.	基本RowId的扫描，在Where查询条件中含有RowId时使用。
