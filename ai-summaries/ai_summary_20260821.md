AI 工作总结 · 2026-08-21
==================================================

生成时间：2026-08-22 09:37:43
团队成员数：32
活跃人数：19
未活跃人数：12

--------------------------------------------------
工作总结详情
--------------------------------------------------

1. 孙恺(Kai)
   优化投放BI功能和自归因。 【需求：
<br>7076414867([【投放BI国服】自定义渠道OneLink解析UA规则优化](https://project.feishu.cn/publishing/story/detail/7076414867))
<br>7074806893([【自归因】OPPO转化回传添加request_id参数](https://project.feishu.cn/publishing/story/detail/7074806893))】

2. 张芮萍(Ruiping)
   优化投放BI功能和导航。 【需求：
<br>7078876125([【投放BI】「公共」导弹窗标记支持特定场景全局禁用](https://project.feishu.cn/publishing/story/detail/7078876125))
<br>7062436729([【投放BI】「海外」投放BI海外接入公共导航](https://project.feishu.cn/publishing/story/detail/7062436729))】

3. 曾凡单(Suzy)
   优化投放BI功能。 【需求：
<br>7067251698([【投放BI】「国服」预警管理1.0](https://project.feishu.cn/publishing/story/detail/7067251698))
<br>7078876125([【投放BI】「公共」导弹窗标记支持特定场景全局禁用](https://project.feishu.cn/publishing/story/detail/7078876125))】

4. 徐晨杰(Tito)
   优化客服系统，修复和添加功能。 【需求：
<br>7067524588([客服系统搭建-m1 ](https://project.feishu.cn/publishing/story/detail/7067524588))
<br>7072926792([【MSDK管理后台】iOS 测试设备相关优化](https://project.feishu.cn/publishing/story/detail/7072926792))】

5. 丁江(Jiang)
   优化iOS测试设备管理，修复AI review问题。 【需求：
<br>7072926792([【MSDK管理后台】iOS 测试设备相关优化](https://project.feishu.cn/publishing/story/detail/7072926792))】

6. 董博(Carl)
   调整first_open事件上报。 【需求：
<br>7078588564([【数据】自定义上报first_open事件](https://project.feishu.cn/publishing/story/detail/7078588564))】

7. 吴超伟(Chaowei)
   增加onesight数据拉取。 【需求：
<br>7069339699([【数据】onesight社媒竞品数据拉取](https://project.feishu.cn/publishing/story/detail/7069339699))】

8. 姜承(JoJo)
   修复素材上传问题。 【需求：
<br>7058918998([【国服】【广告管理平台】FUXI接入巨量直播批量创建](https://project.feishu.cn/publishing/story/detail/7058918998))】

9. 解薇(cheryl)
   修复素材农场打标服务问题。 【需求：
<br>7043811049([【素材农场】接入打标服务 基础流程打通](https://project.feishu.cn/publishing/story/detail/7043811049))】

10. 刘松林(Nelson)
   修复素材农场演示反馈问题。 【需求：
<br>7070000957([【素材农场】素材农场演示反馈 3期迭代](https://project.feishu.cn/publishing/story/detail/7070000957))】

11. 王枫荻(Fengdi)
   增加DAU异常规则。 【需求：
<br>7071915058([【驾驶舱】「海外」核心指标推送增加异常规则](https://project.feishu.cn/publishing/story/detail/7071915058))】

12. 田元林(Candy)
   重构UI验收技能文档。 【需求：
<br>7062007056([【驾驶舱】「海外」实时数据PC端](https://project.feishu.cn/publishing/story/detail/7062007056))】

13. 胡海平(Rambo)
   优化客服系统，修复和添加功能。 【需求：
<br>7067524588([客服系统搭建-m1 ](https://project.feishu.cn/publishing/story/detail/7067524588))】

14. 徐腾飞(Tengfei)
   评估和修复功能。 【需求：
<br>7074913596([KOL 服务组件库迁移](https://project.feishu.cn/publishing/story/detail/7074913596))】

15. 李铭骏(Mingjun)
   优化代码图查询技能，修复多个问题，并更新文档。

16. 祁杰(Jacky)
   升级版本，改造后端，并添加文档。

17. 郑淼(Miao)
   优化构建脚本和修复问题。

18. 马亮亮(Kuroky)
   优化IM功能和UI布局。

19. 张帆(Mlxg)
   优化CI流程。

--------------------------------------------------
MR 评论汇总
--------------------------------------------------

**MR#11** (feat(scan): S8 超时关闭扫描接入——ScanJob 驱动 TimeoutCloseTickets 真实 RPC (IS-M1-S8-TIMEOUT))
- [2026-08-21 20:13] 李铭骏(Mingjun): 方法或变量中不要出现开发信息（备注中可以保留），根据业务来命名

**MR#29** (feat(access): H104 满意度提交 Handler 与卡片真实 WS 下行映射 (IA-M1-S9A-SUBMIT))
- [2026-08-21 10:22] 李铭骏(Mingjun): 提交满意度评价时是否传递项目参数（appId）？ • msdk/rispari/server/im-scheduler              提交:  40  MR:  6  Commit评论:  0  MR评论:  6 分支:chore/codegraph-query-skill, chore/worktree-skill-conflict-resolution, feature/IS-M1-S6-DELAY-delay-task-scan, feature/IS-M1-S8-TIMEOUT-timeout-close-scan, feature/IS-M1-S9B-EXPIRE-satisfaction-expire-scan, feature/r1-devinfo-discipline-extend, milestone/M1 (+9,176 / -1,450) 提交记录（按时间倒序）：

**MR#42** (feat(im-logic): S6 延迟消息服务端树干——DELAY_TASK migration/CRUD/到期投递与 FAILED 语义 (IL-M1-S6-DELAY))
- [2026-08-21 11:00] 李铭骏(Mingjun): 为什么imLogicInternalImpl 要加DelayMessages？imLogicInternalImpl 和 imLogicImpl有什么区别？ • msdk/rispari/server/im-access                 提交:  64  MR: 10  Commit评论:  0  MR评论:  1 分支:chore/codegraph-query-skill, chore/worktree-skill-conflict-resolution, feature/IA-M1-S10B-DEVICE-EVENT-device-changed-downlink, feature/IA-M1-S11-REMARK-remark-handlers-downlink, feature/IA-M1-S12C-QUERY-advanced-filter-handler, feature/IA-M1-S13-HISTORY-player-history-handler, feature/IA-M1-S2S3-ATTACH-MSG-attachment-message-mapping, feature/IA-M1-S6-DELAY-delay-message-handlers, feature/IA-M1-S9A-SUBMIT-satisfaction-handler, feature/r1-devinfo-discipline-extend, milestone/M1 (+21,047 / -643) 提交记录（按时间倒序）：
- [2026-08-21 11:04] 李铭骏(Mingjun): 投递的时候会检查客诉状态吗？

**MR#45** (feat(im-logic): S8 超时候选查询与条件关闭 Internal RPC、系统消息与关闭事件（IL-M1-S8-TIMEOUT）)
- [2026-08-21 14:24] 李铭骏(Mingjun): 这行的改动、判断合理吗？
- [2026-08-21 14:28] 李铭骏(Mingjun): 为什么要连表查询，数据量大时是否消耗资源多、耗时长？是否可以分开查？
- [2026-08-21 14:30] 李铭骏(Mingjun): 有个问题，这些业务处理逻辑存在于dal层是否合理？是否应该在service层或domain层维护业务逻辑？

**MR#46** (feat(message): S2/S3 附件消息——校验/TX1 条件占用接线/元数据回填/Kafka 下行事件 (IL-M1-S2S3-ATTACH-MSG))
- [2026-08-21 15:03] 李铭骏(Mingjun): AttachmentOccupy的业务用处是什么？为什么会有这个结构体?

**MR#9** (feat(s6): S6 延迟投递扫描真实接入（delay_task 数据面 + DeliverDelayedMessage 专用调用）(IS-M1-S6-DELAY))
- [2026-08-21 17:53] 李铭骏(Mingjun): 方法或变量中不要出现开发信息 • msdk/rispari/server/docs                      提交:  25  MR:  3  Commit评论:  0  MR评论:  0 分支:chore/codegraph-query-design, feature/BASE-M1-E2E-S13-history-close-write, feature/BASE-M1-E2E-S7-close-paths-events, feature/BASE-M1-E2E-S9A-satisfaction-submit, feature/BASE-M1-W5-RC-PROMOTE-w5-real-deploy, feature/r1-devinfo-discipline-extend, milestone/M1 (+7,852 / -82) 提交记录（按时间倒序）：
- [2026-08-21 17:55] 李铭骏(Mingjun): 方法或变量中不出现开发信息
- [2026-08-21 18:26] 李铭骏(Mingjun): 不要引入相对位置文件，配置数据直接写入config.yaml中
- [2026-08-21 19:12] 李铭骏(Mingjun): 这几个常量中携带了开发信息，是否应该移除？
- [2026-08-21 19:14] 李铭骏(Mingjun): os.Getenv从哪里获取env？

--------------------------------------------------
未活跃成员
--------------------------------------------------

1. 李孔权(Levir) (未活跃)

2. 覃亮(Daniel) (未活跃)

3. 康鑫博(Xinbo) (未活跃)

4. 王聪(Wilson) (未活跃)

5. 孙鹏 (未活跃)

6. 万映(leo) (未活跃)

7. 田雪健(Storm) (未活跃)

8. 杜民民(Dylan) (未活跃)

9. 王宁(Willem) (未活跃)

10. 张苒(Ran) (未活跃)

11. 朱吉人(Jiren) (未活跃)

12. 王远康(Yuankang) (未活跃)

--------------------------------------------------
说明：以上内容由 AI 自动生成