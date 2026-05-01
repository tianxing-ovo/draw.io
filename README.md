# draw.io

一个用于沉淀后端与计算机基础知识图示的 `draw.io` 仓库。当前共收录 `19` 张 `.drawio` 图，覆盖 `Elasticsearch`、`JUC`、`JVM`、`JWT`、`MySQL` 和 `Network` 等主题，适合面试复习、知识梳理和分享讲解。

## 仓库定位

这个仓库不是可运行项目，而是一组按主题整理的图示资产，主要用于：

- 将抽象概念转化为图示，降低理解门槛
- 在面试复习时快速回顾知识结构
- 为讲解、分享、笔记整理提供统一图示素材

## 内容索引

### Elasticsearch

位于 [`elasticsearch`](./elasticsearch) 目录，当前包含：

- [`同步调用.drawio`](./elasticsearch/同步调用.drawio)
- [`异步通知.drawio`](./elasticsearch/异步通知.drawio)
- [`监听binlog.drawio`](./elasticsearch/监听binlog.drawio)

### JUC

位于 [`juc`](./juc) 目录，当前包含：

- 线程状态：[`线程状态-Java.drawio`](./juc/线程状态-Java.drawio)、[`线程状态-操作系统.drawio`](./juc/线程状态-操作系统.drawio)
- 并发原理：[`Monitor.drawio`](./juc/Monitor.drawio)、[`park原理.drawio`](./juc/park原理.drawio)
- 线程安全示例：[`线程不安全-正数.drawio`](./juc/线程不安全-正数.drawio)、[`线程不安全-负数.drawio`](./juc/线程不安全-负数.drawio)
- 设计模式：
  - [`保护性暂停模式.drawio`](./juc/设计模式/保护性暂停模式.drawio)
  - [`两阶段终止模式.drawio`](./juc/设计模式/两阶段终止模式.drawio)
  - [`生产者消费者模式.drawio`](./juc/设计模式/生产者消费者模式.drawio)

### JVM

位于 [`jvm`](./jvm) 目录，当前包含：

- [`对象头-32位虚拟机.drawio`](./jvm/对象头-32位虚拟机.drawio)

### MySQL

位于 [`mysql`](./mysql) 目录，当前包含：

- [`B+Tree.drawio`](./mysql/B+Tree.drawio)
- [`BTree.drawio`](./mysql/BTree.drawio)
- [`垂直拆分.drawio`](./mysql/垂直拆分.drawio)
- [`水平拆分.drawio`](./mysql/水平拆分.drawio)

### Network

位于 [`network`](./network) 目录，当前包含：

- [`BIO.drawio`](./network/BIO.drawio)

### JWT

仓库根目录当前包含：

- [`JWT.drawio`](./JWT.drawio)

## 目录结构

```text
draw.io
├─ elasticsearch
│  ├─ 同步调用.drawio
│  ├─ 异步通知.drawio
│  └─ 监听binlog.drawio
├─ juc
│  ├─ 设计模式
│  │  ├─ 两阶段终止模式.drawio
│  │  ├─ 保护性暂停模式.drawio
│  │  └─ 生产者消费者模式.drawio
│  ├─ Monitor.drawio
│  ├─ park原理.drawio
│  ├─ 线程不安全-正数.drawio
│  ├─ 线程不安全-负数.drawio
│  ├─ 线程状态-Java.drawio
│  └─ 线程状态-操作系统.drawio
├─ jvm
│  └─ 对象头-32位虚拟机.drawio
├─ mysql
│  ├─ B+Tree.drawio
│  ├─ BTree.drawio
│  ├─ 垂直拆分.drawio
│  └─ 水平拆分.drawio
├─ network
│  └─ BIO.drawio
├─ JWT.drawio
├─ LICENSE
└─ README.md
```

## 如何查看和编辑

推荐使用以下任一种方式打开 `.drawio` 文件：

1. 使用 [diagrams.net](https://app.diagrams.net/) 在线打开本地文件
2. 使用 diagrams.net Desktop 本地打开并编辑
3. 使用支持 draw.io 的 IDE 插件进行预览和修改

常见操作流程：

1. 打开对应的 `.drawio` 文件
2. 修改图形、连接线、颜色和说明文字
3. 按需导出为 `PNG`、`SVG` 或 `PDF`

## 适用场景

- 面试前按专题快速复盘
- 学习新知识时先搭建整体框架，再补充细节
- 给博客、分享稿、课程讲义补充图示
- 团队内部交流时统一术语和结构表达

## 维护约定

- 新图优先按专题归档到对应目录
- 文件名尽量直接表达主题，避免含糊命名
- 一张图优先只讲清一个核心概念
- 同一主题持续扩展时，优先拆成多张图而不是无限追加
- 提交前建议导出预览图自查一次，确认文字和连线布局没有错位

## 后续可扩展方向

- `elasticsearch` 下补充索引设计、分词、搜索流程、集群架构等主题
- `jvm` 下补充类加载、GC、运行时数据区等主题
- `mysql` 下补充索引失效、事务隔离、MVCC 等主题
- `network` 下继续补充 `NIO`、`Netty`、`TCP/IP` 相关图示
- 根目录可以增加按专题汇总的导航图或总览图

## 许可证

本仓库基于 [Apache License 2.0](./LICENSE) 开源。
