# 大型网站Java技能图谱，菜鸟进阶专家之路
不想成为专家的程序员不是好程序员，本着简单直接的原则，力争以技能图谱的方式清晰地展示大型网站后端的全貌。
这个项目源于本人之前读过的相关大型网站架构系列的书籍《大型网站技术架构 核心原理与案例分析》、《大型网站系统与Java中间件开发实践》。
介于书中内容过于宽泛，可操作性差，所以希望通过图谱的方式直观展示，增强可操作性。

> 目标：根据图谱给出的学习方向逐步提升自己，一步步走向专家级程序员

## 好文推荐
> [如何在三年内成长为一名技术专家](http://ifeve.com/%E3%80%8A%E9%98%BF%E9%87%8C%E6%84%9F%E6%82%9F%E3%80%8B%E5%A6%82%E4%BD%95%E5%9C%A8%E4%B8%89%E5%B9%B4%E5%86%85%E6%88%90%E9%95%BF%E4%B8%BA%E4%B8%80%E5%90%8D%E6%8A%80%E6%9C%AF%E4%B8%93%E5%AE%B6/)
> 
> [实战解析—论三年内快速成长为一名技术专家](http://ifeve.com/%E5%AE%9E%E6%88%98%E8%A7%A3%E6%9E%90-%E8%AE%BA%E4%B8%89%E5%B9%B4%E5%86%85%E5%BF%AB%E9%80%9F%E6%88%90%E9%95%BF%E4%B8%BA%E4%B8%80%E5%90%8D%E6%8A%80%E6%9C%AF%E4%B8%93%E5%AE%B6/)

## 专家程序员的基本要求

* **技术能力**：扎实的基础能力，在技术上要有技术亮点，用过的框架要知道其技术原理，能**独立**解决各种技术问题，具备分布式系统的开发经验，比较强的实战能力
* **项目经验**：能架构和负责多个系统，并规划系统的未来能力，在某个领域达到专家水平，可以是某个业务领域，也可以是某个技术领域

## 协作平台

* 在线协作平台（密码需要加微信确定参与领取）：[http://www.processon.com](http://www.processon.com/team/invite/59e96291e4b08b9e917eb388/pqOKGvSu)
* Github：[https://github.com/rhwayfun/java-skill-graph](https://github.com/rhwayfun/java-skill-graph)
* 博客：[http://blog.csdn.net/u011116672](http://blog.csdn.net/u011116672)

## 参与方式

* 创建issue，标明ProcessOn账号，加微信（ZCB2012001）确认参与
* 在ProcessOn编辑不同模块的图谱
* 在issues添加你的Github ID

## 参与协作

1.到源码仓库`https://github.com/rhwayfun/java-skill-graph`，点击`Fork`

2.如果之前已经 fork 过，请确保你的本地版本库是最新的，如果不是，请马上进行同步

```shell
## 先clone到本地仓库
git clone https://github.com/你的Github ID/java-skill-graph.git

## 保持和远程仓库同步
git remote add upstream https://github.com/rhwayfun/java-skill-graph.git

## 拉取远程仓库最新代码
git fetch upstream

## 合并到本地仓库
git merge upstream/master

## 及时更新最新改动
git pull --rebase
```

3.添加之前参与模块的图谱的撰写，每个模块的名字已事先确定好

4.如果模块的图谱已经绘制完毕，导出成图片格式，并将文件放到`image`文件夹下面，命名与`source`中的命名保持一致，修改到`source`对应的文件URL

5.提交到Github后，在自己仓库下提个Pull Request，我这边审核后合并到主仓库

## 目录简介

本图谱目前涵盖以下内容：

``` 

└── 计算机基础

└── 算法与数据结构

└── Java编程

└── JVM虚拟机

└── 设计模式

└── Linux

└── 分布式系统

└── 大数据

└── 职业生涯

└── 学习方法与心态

```

## 内容统计

|      | 标题                                       | 状态   | 作者                                       | 审核                                       |
| ---- | ---------------------------------------- | ---- | ---------------------------------------- | ---------------------------------------- |
| 001 | [计算机基础](./source/computer-basics.md) |  完善中    |  [rhwayfun](https://github.com/rhwayfun) |  |
| 002 | [算法与数据结构](./source/algorithm-data-structure.md) |  待认领    |  |  |
| 003 | [大数据](./source/bigdata.md) |  待认领    |  |  |
| 004 | [设计模式](./source/design-patterns.md) |  编辑中    | [CloudPai](https://github.com/CloudPai) |  |
| 005 | [分布式系统](./source/distributed-system.md) |  完善中    | [HoldDie](https://github.com/HoldDie) |  |
| 006 | [Java编程](./source/java-programming.md) |  编辑中    | [bryancrash](https://github.com/bryancrash) |  |
| 007 | [JVM虚拟机](./source/jvm.md) |  待认领    |  |  |
| 008 | [Linux操作系统](./source/linux.md) |  待认领    |  |  |
| 009 | [学习方法与心态](./source/study-method-mentality.md) |  编辑中    | [rhwayfun](https://github.com/rhwayfun) |  |



## 技能图谱
目前第一版把全部内容都放在一个文件了，后面为了管理和维护方便，考虑按模块拆出来，一个模块一个文件。欢迎加入。

**[v1.0.0](graph.md)**

## 更多内容
更全更牛逼的技能图谱，等你来完善O(∩_∩)O哈哈~
持续更新中。。。

## License

采用[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)协议进行许可。

