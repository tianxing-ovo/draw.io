# draw.io

一个用于沉淀后端知识点图示的 `draw.io` 仓库，当前内容主要覆盖 `JUC`、`JVM`、`MySQL` 和 `JWT` 相关主题

## 仓库定位

这个仓库不是可运行项目，而是一个按专题整理的图示集合，适合用于：

- 面试复习时快速回顾知识结构
- 学习过程中将抽象概念转化为图示
- 分享或讲解并发、JVM、MySQL 等核心原理

## 目录结构

```text
.
├─ JWT.drawio
├─ juc
│  ├─ Monitor.drawio
│  ├─ park原理.drawio
│  ├─ 线程不安全-正数.drawio
│  ├─ 线程不安全-负数.drawio
│  ├─ 线程状态-Java.drawio
│  ├─ 线程状态-操作系统.drawio
│  └─ 设计模式
│     ├─ 两阶段终止模式.drawio
│     ├─ 保护性暂停模式.drawio
│     └─ 生产者消费者模式.drawio
├─ jvm
│  └─ 对象头-32位虚拟机.drawio
└─ mysql
   ├─ BTree.drawio
   ├─ B+Tree.drawio
   ├─ 垂直拆分.drawio
   └─ 水平拆分.drawio
```

## 当前内容

### JUC

- 线程状态在 Java 与操作系统层面的差异
- `Monitor` 与 `park/unpark` 相关原理
- 线程不安全示例
- 常见并发设计模式：
  - 保护性暂停模式
  - 两阶段终止模式
  - 生产者消费者模式

### JVM

- 32 位虚拟机场景下的对象头结构

### MySQL

- `BTree` 与 `B+Tree`
- 水平拆分与垂直拆分

### JWT

- `JWT` 基本结构图

## 如何查看和编辑

推荐使用以下任一种方式打开 `.drawio` 文件：

1. 使用 [diagrams.net](https://app.diagrams.net/) 在线打开本地文件
2. 使用 diagrams.net Desktop 打开并编辑
3. 使用支持 draw.io 的 IDE 插件进行预览

常见操作流程：

1. 打开对应的 `.drawio` 文件
2. 修改图形、连接线、说明文字
3. 按需导出为 `PNG`、`SVG` 或 `PDF`

## 维护建议

- 按主题新建目录，避免所有图堆在根目录
- 文件名尽量直接表达主题，便于检索
- 优先保持一张图只讲清一个核心概念
- 如果同一主题持续扩展，建议拆为多张图而不是无限追加

## 许可证

本仓库基于 [Apache License 2.0](LICENSE) 开源
