# 量潮搜索工程

本页是领域入口：结构与去处。为什么做、做成什么样、哪些不做在 [意图仓](data/intention)；边界与职责（检索索引侧、与元工程的分工）的事实源在 [README](README.md)。

## 系统结构

系统分前台与后台两层。

**前台**是搜索界面，形态与通用搜索引擎一致。它将各平台的信息打通，纳入同一次查询并返回统一结果集，用户在结果之上判断自己下一步要做什么。

**后台**是搜索云，含两部分：

- 搜索策略：多种策略可自由组合，负责优化前台界面与各搜索入口的检索质量。
- 搜索机制：以自有的公开知识库为基础，加入市场公开数据，结合大模型完成智能判断。

## 去处

- 边界与子模块清单：[README](README.md)
- 意图：`data/intention`（[intro/index.md](data/intention/intro/index.md））
- 路线图：`data/roadmap`
- 语境：`data/context`（含 [OneBase 目录指南](data/context/library/onebase.md)）
- 教程：`docs/tutorial`（[从零写一个搜索程序](docs/tutorial/intro/loop.md)）
- 实验室：`examples/quanttide-search-lab`
