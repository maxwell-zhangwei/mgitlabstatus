AI 工作总结 · 2026-08-20
==================================================

生成时间：2026-08-21 09:38:47
团队成员数：32
活跃人数：20
未活跃人数：12

--------------------------------------------------
工作总结详情
--------------------------------------------------

1. 孙恺(Kai)
   投放BI国服广告主自归因应用配置采集事件配置更新（10:56） 【需求：
<br>7065577164([【投放BI国服】广告主自归因-应用配置-采集事件配置](https://project.feishu.cn/publishing/story/detail/7065577164))
<br>7058918998([【国服】【广告管理平台】FUXI接入巨量直播批量创建](https://project.feishu.cn/publishing/story/detail/7058918998))】

2. 曾凡单(Suzy)
   投放BI海外增加创号包体维度和筛选框（14:24） 【需求：
<br>7055636723([【投放BI海外】增加创号包体维度和筛选框](https://project.feishu.cn/publishing/story/detail/7055636723))
<br>7068383459([【投放BI】「国服」B站Oauth升级表单兼容改造](https://project.feishu.cn/publishing/story/detail/7068383459))】

3. 覃亮(Daniel)
   素材农场作业任务ID增加前缀（15:45） 【需求：
<br>7067932963([【素材农场】素材农场作业主流程页面开发-2期](https://project.feishu.cn/publishing/story/detail/7067932963))
<br>7075110488([【海外】广告管理平台 MUSE素材查询列表优化](https://project.feishu.cn/publishing/story/detail/7075110488))】

4. 丁江(Jiang)
   优化 MSDK 管理后台 iOS 测试设备相关功能（20:28） 【需求：
<br>7072926792([【MSDK管理后台】iOS 测试设备相关优化](https://project.feishu.cn/publishing/story/detail/7072926792))】

5. 张芮萍(Ruiping)
   投放BI国服 B站Oauth升级表单兼容改造（15:04） 【需求：
<br>7068383459([【投放BI】「国服」B站Oauth升级表单兼容改造](https://project.feishu.cn/publishing/story/detail/7068383459))】

6. 刘松林(Nelson)
   修复素材农场演示反馈中的问题，包括图像恢复和视频处理（20:01） 【需求：
<br>7070000957([【素材农场】素材农场演示反馈 3期迭代](https://project.feishu.cn/publishing/story/detail/7070000957))】

7. 徐晨杰(Tito)
   客服系统搭建，优化 Dockerfile 和 Nginx 配置（16:44） 【需求：
<br>7067524588([客服系统搭建-m1 ](https://project.feishu.cn/publishing/story/detail/7067524588))】

8. 万映(leo)
   MSDK 文档静态网页框架搭建与优化（20:48） 【需求：
<br>7074859873([【MSDK接入】msdk文档静态网页框架搭建](https://project.feishu.cn/publishing/story/detail/7074859873))】

9. 胡海平(Rambo)
   客服系统搭建，优化 WebSocket 日志和附件上传处理（18:40） 【需求：
<br>7067524588([客服系统搭建-m1 ](https://project.feishu.cn/publishing/story/detail/7067524588))】

10. 李孔权(Levir)
   开发环境配置更新，包括数据库地址和中间件地址（16:28） 【需求：
<br>7065301787([【MSDK管理后台】iOS重签包](https://project.feishu.cn/publishing/story/detail/7065301787))】

11. 孙鹏
   MSDK 管理后台 iOS 重签包页面优化（16:25） 【需求：
<br>7065301787([【MSDK管理后台】iOS重签包](https://project.feishu.cn/publishing/story/detail/7065301787))】

12. 王枫荻(Fengdi)
   核心指标推送增加异常规则（19:32） 【需求：
<br>7071915058([【驾驶舱】「海外」核心指标推送增加异常规则](https://project.feishu.cn/publishing/story/detail/7071915058))】

13. 田雪健(Storm)
   推送截图导航状态注入修复（21:34） 【需求：
<br>7071843945([【投放BI】「国服」添加自定义指标](https://project.feishu.cn/publishing/story/detail/7071843945))】

14. 叶明(Ming)
   删除部分AI文档，优化驾驶舱实时数据（16:54） 【需求：
<br>7056369006([【数据】驾驶舱实时数据](https://project.feishu.cn/publishing/story/detail/7056369006))】

15. 田元林(Candy)
   调整实时数据国家表格列宽（15:00） 【需求：
<br>7062007056([【驾驶舱】「海外」实时数据PC端](https://project.feishu.cn/publishing/story/detail/7062007056))】

16. 马亮亮(Kuroky)
   iOS SDK 测试和修复，包括 WebP 图像加载和单元测试（11:55）

17. 郑淼(Miao)
   imscheduler 生产环境启动脚本添加（14:06）

18. 李铭骏(Mingjun)
   多文档调整与代码重构，优化历史对话功能（20:43）

19. 徐腾飞(Tengfei)
   测试设计工具优化，知识提取与文档规范化（16:14）

20. 祁杰(Jacky)
   新增 openreplay 集成（11:11）

--------------------------------------------------
MR 评论汇总
--------------------------------------------------

**MR#24** (feat(close): H103/H302/H303 关闭/回绝真实 Handler 与关闭事件真实 WS 下行映射 (IA-M1-S7-CLOSE))
- [2026-08-20 17:40] 李铭骏(Mingjun): 还会有别的CloseConversationByXXX方法吗？为什么不和ByAgent,Reject等方法放在一起？ • msdk/rispari/server/im-scheduler              提交:  11  MR:  2  Commit评论:  0  MR评论:  0 分支:chore/CURRENT-MD-SCHEDULE-SPLIT-progress-cleanup, develop, feature/IS-M1-P016-ERRORCODE-CONSUME-error-code-int64, feature/dev-conf-self-contained, milestone/M1 (+7,666 / -255) 提交记录（按时间倒序）：
- [2026-08-20 17:45] 李铭骏(Mingjun): 怎么感觉类似的常量和方法在很多地方都见过？是否可以统一处理
- [2026-08-20 17:47] 李铭骏(Mingjun): 为什么分散在两个proto下？（conversat‎ion.proto‎，ticketcl‎ose.proto‎）
- [2026-08-20 18:31] 李铭骏(Mingjun): 为何只有一个枚举？

**MR#25** (refactor(identity): H-21 专项——身份主体解析归一化到 middleware 双 helper (handoff H-21))
- [2026-08-20 20:31] 李铭骏(Mingjun): 为什么这里AgentSubjectFrom两个参数？下面PlayerSubjectFrom一个参数？

**MR#33** (feat(history): C 端历史客诉查询——开关/两年窗口/20 条分页 ListHistoryConversations 真实实现 (IL-M1-S13-HISTORY))
- [2026-08-20 16:03] 李铭骏(Mingjun): 这个服务命名是否太宽泛了 • msdk/rispari/server/docs                      提交:  44  MR:  6  Commit评论:  0  MR评论:  1 分支:feature/BASE-M1-E2E-S12B-workbench-unload, feature/BASE-M1-E2E-S17A-attachment-issue-upload, feature/BASE-M1-E2E-S2A-message-send-ack, feature/BASE-M1-E2E-S2A-post-merge-checklist, feature/BASE-M1-E2E-S4-pull-reconnect-paging, feature/BASE-M1-E2E-S5-read-cursor-event, feature/BASE-M1-ENV-DB-ISOLATION, feature/BASE-M1-W4-RC-PROMOTE-w4-real-deploy, feature/CONTRACT-P015-RENAME-S13-HISTORY-TICKETS, feature/CONTRACT-P016-ERRORCODE-INT64, feature/CONTRACT-P017-SATISFACTION-HISTORY-FIELD-ONLY-ADD, milestone/M1 (+11,793 / -1,447) 提交记录（按时间倒序）：
- [2026-08-20 17:03] 李铭骏(Mingjun): 到底是获取历史对话还是客诉？gateway对应的接口是什么？
- [2026-08-20 19:01] 李铭骏(Mingjun): 为什么这个方法在domain/converstaion领域下？

**MR#34** (feat(satisfaction): S9-A 满意度提交面交付——1~5 星提交 + satisfactionId 幂等 + 提交即归档 (IL-M1-S9A-SUBMIT))
- [2026-08-20 16:29] 李铭骏(Mingjun): 提交满意度之后，是否有事件、接口触发后续操作？
- [2026-08-20 16:30] 李铭骏(Mingjun): SatisfactionSubmit 为什么命名后缀Submit？
- [2026-08-20 16:32] 李铭骏(Mingjun): 为什么错误string字段叫“ErrCode”？
- [2026-08-20 16:56] 李铭骏(Mingjun): “mysql=%v, player=%v, messages=%v”和“projectRepo != nil, playerRepo != nil, messageRepo != nil” 不在一个维度上

**MR#35** (chore(skills): im-task-playbook 回填范围边界优化 (IL-M1-S13-HISTORY))
- [2026-08-20 20:27] 李铭骏(Mingjun): 4,5,6都是当前任务收尾要处理的吗？如果不是，是否可以剥离，避免信息干扰
- [2026-08-20 20:28] 李铭骏(Mingjun): 这些到底是要做还是不要做的，能不能把要做的列在这，不要做的在其他地方说明

**MR#37** (feat(BASE-M1-ENV-DB-ISOLATION): 开发/联调/E2E 三层 schema 隔离)
- [2026-08-20 11:53] 李铭骏(Mingjun): 这个从何而来 • msdk/rispari/server/im-access                 提交:  38  MR:  5  Commit评论:  0  MR评论:  5 分支:chore/CURRENT-MD-SCHEDULE-SPLIT-progress-cleanup, develop, feature/IA-M1-P016-ERRORCODE-CONSUME-error-code-int64, feature/IA-M1-S13-HISTORY-player-history-handler, feature/IA-M1-S5-READ-CURSOR-read-event-downlink, feature/IA-M1-S7-CLOSE-close-reject-handlers, feature/IA-M1-S9A-SUBMIT-satisfaction-handler, feature/dev-conf-self-contained, feature/handoff-H-21-identity-normalization, milestone/M1 (+22,096 / -1,834) 提交记录（按时间倒序）：

--------------------------------------------------
未活跃成员
--------------------------------------------------

1. 康鑫博(Xinbo) (未活跃)

2. 姜承(JoJo) (未活跃)

3. 张帆(Mlxg) (未活跃)

4. 王聪(Wilson) (未活跃)

5. 解薇(cheryl) (未活跃)

6. 杜民民(Dylan) (未活跃)

7. 王宁(Willem) (未活跃)

8. 张苒(Ran) (未活跃)

9. 董博(Carl) (未活跃)

10. 吴超伟(Chaowei) (未活跃)

11. 朱吉人(Jiren) (未活跃)

12. 王远康(Yuankang) (未活跃)

--------------------------------------------------
说明：以上内容由 AI 自动生成