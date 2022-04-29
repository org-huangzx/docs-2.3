# 高效任务监控运维

完成数据集成、开发和服务后，便需要保证系统稳定运行。如何以较低的成本达到更好的监控效果、如何评估失败任务对下游的影响以及恢复时间是任务运维需解决的问题。

任务运维中心包括通知管理、通知明细、工作流运维、运行总览及运行明细，用于展示当前需重点关注的运维指标、任务运行状态、调度资源变化趋势，以及离线同步、实时同步任务的运行状态分布、数据同步进度等集成信息，有利于提升任务运维效率。

## 结果查询

工作流运行成功后，可进入 **数据开发 > 即席查询** 查看数据表结果数据。

1. 在编辑器中输入查询 SQL，点击 **执行**。
2. 点击右上角记录图标可查看即席查询记录。

![](https://terminus-paas.oss-cn-hangzhou.aliyuncs.com/paas-doc/2021/08/20/1e29d96b-9749-4148-98c0-b41d0d263c20.gif)

## 运行总览

进入 **数据开发 > 任务运维 > 运行总览** 可查看任务运行整体情况，包括今日周期明细执行汇总、周期明细完成情况、执行时长排行以及最近 30 天出错排行。

![](https://terminus-paas.oss-cn-hangzhou.aliyuncs.com/paas-doc/2021/08/20/dd6fced5-e6fa-4fb8-a855-f8c8f32cfd1e.gif)

## 运行明细

进入 **数据开发 > 任务运维 > 运行明细** 可查看数据任务运行状态、运行进度、开始时间、结束时间等信息，同时支持根据不同条件筛选工作流以及批量操作。

## 工作流运维

进入 **数据开发 > 任务运维 > 工作流运维** 可查询工作流，并对工作流进行批量操作，包括批量启动、批量停止、批量定时等。点击工作流行 **详情** 可查看该工作流的依赖情况及运行明细。

![](http://terminus-paas.oss-cn-hangzhou.aliyuncs.com/paas-doc/2021/11/29/df945193-23d0-4d32-a395-6dc76d9bdedc.gif)

## 通知管理

进入 **数据开发 > 任务运维 > 通知管理** 可配置工作流运行状态通知。

1. 点击 **新增通知**，并填写相关信息。

   | 参数     | 说明                                         | 是否必填 |
   | -------- | -------------------------------------------- | -------- |
   | 通知名称 | 通知名称                                     | 是       |
   | 通知项   | 工作流运行失败/工作流开始运行/工作流运行成功 | 是       |
   | 影响范围 | 监控工作流范围                               | 是       |
   | 通知方式 | 当前仅支持邮件                               | 是       |
   | 通知对象 | 填写对象信息（用户名、邮件地址、电话）       | 是       |

2. 可在通知管理页面，对已配置的工作流进行停用、编辑与删除操作。


![](https://terminus-paas.oss-cn-hangzhou.aliyuncs.com/paas-doc/2021/08/20/6efef98d-af2a-4ae5-8c15-34c7268adb2b.gif)

## 通知明细

进入 **数据开发 > 任务运维 > 通知明细** 可查看已产生的通知信息。

![](http://terminus-paas.oss-cn-hangzhou.aliyuncs.com/paas-doc/2021/11/29/196f5beb-5e51-41de-a1b7-e1b4b4dc67f7.gif)