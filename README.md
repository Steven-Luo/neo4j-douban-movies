# 使用Neo4j为豆瓣电影构建电影知识图谱

使用Neo4j将豆瓣电影原始数据构建为知识图谱，可以方便地实现最短路劲、多跳查询等传统关系型数据库并不擅长的操作，此外还有一些列其他的好处。

原始数据来源：http://data.openkg.cn/dataset/douban-movie-kg

## 构建过程

构建过程已发布在微信公众号上，欢迎大家阅读。

## 效果展示

### Schema

共构建了5中节点，6种关系，Schema如下：

![](assets/schema.png)

### 查询效果

最短路径

![](assets/shortest-path.png)