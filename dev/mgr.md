# 开发管理

## 介绍
* 目标：拥抱变化，进度可控。
* 方法：快速迭代，确保产品发布的快速和弹性。
* 模式：[增量模型](https://baike.baidu.com/item/%E5%A2%9E%E9%87%8F%E6%A8%A1%E5%9E%8B)

## 阶段
| 阶段 | 工作 | 交付 |
| :-: | - | - |
| 需求 | 需求分析 | 需求说明书 |
| 设计 | 原型设计，界面设计，系统设计 | 原型，界面，设计说明书，数据字典 |
| 开发 | 代码开发 | 源代码 |
| 测试 | 单元测试，集成测试，验收 | 测试报告 |
| 交付 | 交付材料编写 | 安装手册，使用手册 |

## 开发模型
| 项 | 说明 |
| :-: | - |
| 产品 | 管理需求、计划和发布 |
| 计划 | 需求属于计划 |
| 项目 | 管理任务开发，分配开发资源。相当于敏捷开发里的迭代 |
| 版本 | 测试用 |
| 发布 | 发布用 |

* [资料](http://www.jianshu.com/p/24e240373b6d)

## 开发实例
### 大项目
* 1个产品对应n个计划
* 1个计划对应1/n个发布(如有bug，则可能有n个发布)

| 项 | 关系 |
| :-: | - |
| 产品 | 1产品 -> n计划 |
| 计划 | 1计划 -> 1项目 |
| 项目 | 1项目 -> n版本 |
| 版本 | 1版本 -> 1发布 |
| 发布 |  |

### 中小项目
* 1个产品对应1个计划
* 1个计划对应1个项目，n个版本和n个发布
* 任务状态需有迭代控制(如未开始)

| 项 | 关系 |
| :-: | - |
| 产品 | 1产品 -> 1计划 |
| 计划 | 1计划 -> 1项目 |
| 项目 | 1项目 -> n版本 |
| 版本 | 1版本 -> 1发布 |
| 发布 |  |

## 参考
### WBS
- [工作分解结构(Work Breakdown Structure)](http://www.mypm.net/special/wbs/)

### 项目管理过程组与知识领域表
* 5大项目管理过程组：启动过程组、规划过程组、执行过程组、监控过程组、收尾过程组
* 9大项目管理知识领域：项目整合管理、项目范围管理、项目时间管理、项目成本管理、项目质量管理、项目人力资源管理、项目沟通管理、项目风险管理、项目采购管理
* 42个项目管理过程

| 领域 | 启动 | 规划 | 执行 | 监控 | 收尾 |
| :-: | - | - | - | - | - |
| 项目整合管理 | 1.制定项目章程 | 2.制定项目管理计划 | 3.指导与管理项目执行 | 4.监控项目工作；5.实施整体变更控制 | 6.结束项目或阶段 |
| 项目范围管理 | 无 | 1.收集需求；2.定义范围；3.创建工作分解结构 | 无 | 4.核实范围；5.控制范围 | 无 |
| 项目时间管理 | 无 | 1.定义活动；2.排列活动顺序；3.估算活动资源；4.估算活动持续时间；5.制定进度计划 | 无 | 6.控制进度 | 无 |
| 项目成本管理 | 无 | 1.估算成本；2.制定预算 | 无 | 3.控制成本 | 无 |
| 项目质量管理 | 无 | 1.规划质量 | 2.实施质量保证 | 3.实施质量控制 | 无 |
| 项目人力资源管理 | 无 | 1.制定人力资源计划 | 2.组建项目团队；3.建设项目团队；4.管理项目团队 | 无 | 无 |
| 项目沟通管理 | 1.识别干系人 | 2.规划沟通 | 3.发布信息；4.管理干系人期望 | 5.报告绩效 | 无 |
| 项目风险管理 | 无 | 1.规划风险管理；2.识别风险；3.实施定性风险分析；4.实施定量风险分析；5.规划风险应对 | 无 | 6.监控风险 | 无 |
| 项目采购管理 | 无 | 1.规划采购 | 2.实施采购 | 3.管理采购 | 4.结束采购 |
