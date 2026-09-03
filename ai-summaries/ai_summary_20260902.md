AI 工作总结 · 2026-09-02
==================================================

生成时间：2026-09-03 09:38:35
团队成员数：32
活跃人数：23
未活跃人数：8

--------------------------------------------------
工作总结详情
--------------------------------------------------

1. 李孔权(Levir)
   日志采集格式改造与 IPA 签名功能。 【需求：
<br>6990031498([【MSDK】Apple Consumption 退款倾向能力](https://project.feishu.cn/publishing/story/detail/6990031498))
<br>7076999931([【MSDK】日志采集从flume切换vector及日志格式改造](https://project.feishu.cn/publishing/story/detail/7076999931))
<br>7065301787([【MSDK管理后台】iOS重签包](https://project.feishu.cn/publishing/story/detail/7065301787))】

2. 田雪健(Storm)
   Nuwa MCP 工具添加 Google 广告查询工具。 【需求：
<br>7102954175([【Ada】Nuwa MCP tools - Campaign/AdGroup detail 工具](https://project.feishu.cn/publishing/story/detail/7102954175))
<br>7099659398([【素材农场】自动投放FB 预研与测试验证](https://project.feishu.cn/publishing/story/detail/7099659398))】

3. 覃亮(Daniel)
   鸿蒙平台接入与马甲包开发。 【需求：
<br>7078533220([【国服】广告管理平台-鸿蒙平台接入和马甲包](https://project.feishu.cn/publishing/story/detail/7078533220))
<br>7078463913([【素材农场】4期用户反馈 功能优化](https://project.feishu.cn/publishing/story/detail/7078463913))】

4. 吴超伟(Chaowei)
   数据批量处理与舆情分析调整。 【需求：
<br>7075470775([【数据】mlbb十周年情感分析结果表](https://project.feishu.cn/publishing/story/detail/7075470775))
<br>7033223685([【数据】舆情分析支持ml国服](https://project.feishu.cn/publishing/story/detail/7033223685))】

5. 姜承(JoJo)
   修复本地素材重开抽屉问题与媒体账户精确匹配。 【需求：
<br>7099727633([【国服】广告管理平台 拉取BI未配置代理商与产品阶段的账户时提示优化](https://project.feishu.cn/publishing/story/detail/7099727633))】

6. 杜民民(Dylan)
   实时任务优化异常处理与 gitignore 更新。 【需求：
<br>7075256889([【自归因】实时任务优化异常处理逻辑](https://project.feishu.cn/publishing/story/detail/7075256889))】

7. 万映(leo)
   MSDK 文档静态网页搭建与优化。 【需求：
<br>7080537853([【MSDK接入】msdk文档静态网页内容搭建](https://project.feishu.cn/publishing/story/detail/7080537853))】

8. 曾凡单(Suzy)
   预警管理权限验证与展点消受限逻辑优化。 【需求：
<br>7067251698([【投放BI】「国服」预警管理1.0](https://project.feishu.cn/publishing/story/detail/7067251698))】

9. 王枫荻(Fengdi)
   内网 harbor 迁移与国服实时接口实现。 【需求：
<br>7094852100([【驾驶舱】「国服」实时数据](https://project.feishu.cn/publishing/story/detail/7094852100))】

10. 张芮萍(Ruiping)
   预测趋势图修复与预测趋势分析。 【需求：
<br>7077983518([【投放BI】「海外」预测趋势与误差分析](https://project.feishu.cn/publishing/story/detail/7077983518))】

11. 胡海平(Rambo)
   客服系统搭建，修复文本输入限制与消息归档问题。 【需求：
<br>7067524588([客服系统搭建-m1 ](https://project.feishu.cn/publishing/story/detail/7067524588))】

12. 孙鹏
   预警管理逻辑处理与列表字段对齐。 【需求：
<br>7067251698([【投放BI】「国服」预警管理1.0](https://project.feishu.cn/publishing/story/detail/7067251698))】

13. 田元林(Candy)
   国服实时数据接入 SSE 通知。 【需求：
<br>7094852100([【驾驶舱】「国服」实时数据](https://project.feishu.cn/publishing/story/detail/7094852100))】

14. 徐晨杰(Tito)
   满意度时间行更新与客服系统搭建。 【需求：
<br>7067524588([客服系统搭建-m1 ](https://project.feishu.cn/publishing/story/detail/7067524588))】

15. 王聪(Wilson)
   MCP 模型指导与 Facebook MCP 接入。

16. 丁江(Jiang)
   e2e 测试工具与 bizreport 文档重构。

17. 李铭骏(Mingjun)
   文档修订与评审，包括已读语义场景和台账行同步。

18. 孙恺(Kai)
   MR 评论，关注 flag 和缓存设置。

19. 张帆(Mlxg)
   图片下载优化与 iOS SDK 修复。

20. 王远康(Yuankang)
   账号列表优化与广告管理平台功能改进。

21. 郑淼(Miao)
   更新 README.md 文件。

22. 徐腾飞(Tengfei)
   修复服务端文档锚点链接问题。

23. 马亮亮(Kuroky)
   修复消息方向与列表布局问题。

--------------------------------------------------
MR 评论汇总
--------------------------------------------------

**MR#101** (feat(ticket): 满意度提交实时通知事件生产面 (IL-M1-P040-SAT-SUBMITTED-EVENT))
- [2026-09-02 14:10] 李铭骏(Mingjun): 这里VisibleScopeAll，是否意味着提交评价请求的客户端也会收到事件消息 • msdk/rispari/server/player-gateway            提交:   8  MR:  2  Commit评论:  0  MR评论:  0 分支:develop, feature/PG-11-P040-SAT-SUBMITTED-EVENT-sat-submitted-event, milestone/M1 (+896 / -64) 提交记录（按时间倒序）： 1. 237fbdd4  Merge branch 'milestone/M1' into 'develop' 分支: develop
- [2026-09-02 14:23] 李铭骏(Mingjun): 对于满意度card的检查方法仅此一处吗？如果存在多处评估下是否可以聚合呢，保持领域方法的内聚

**MR#113** (docs(M1): DownMessage 下行收到确认语义同步（时序图补齐 + ACK_OK 钉死）(BASE-M1-DOWNACK-DOCS))
- [2026-09-02 09:41] 李铭骏(Mingjun): 这条备注有必要放在这吗，有更合适的地方吗？ • msdk/rispari/server/im-logic                  提交:   9  MR:  2  Commit评论:  0  MR评论:  2 分支:develop, feature/IL-M1-P040-SAT-SUBMITTED-EVENT-sat-submitted-event, milestone/M1 (+1,798 / -112) 提交记录（按时间倒序）： 1. 591e7d8f  Merge branch 'milestone/M1' into 'develop' 分支: develop
- [2026-09-02 09:41] 李铭骏(Mingjun): 这条备注有必要放在这吗，有更合适的地方吗？
- [2026-09-02 09:46] 李铭骏(Mingjun): “服务端消费面不校验下行 Ack 的 `status`”，为什么不校验？是不是不合理？

**MR#126** (fix(biz-report): 竞速/登录链路 SQL 兼容新旧事件（OR aws_upload_did_and_aid）)
- [2026-09-02 02:05] 丁江(Jiang): 无须处理（logymd & server_time/create_time同时存在，不会因为logymd+1导致误差，仍然以用户约束的start_time ~ end_time为查询范围；logymd+1为了兜住sever_time/create_time跨天的case） • mirrorsphere/forge                            提交:   2  MR:  2  Commit评论:  0  MR评论:  0 分支:master, test 提交记录（按时间倒序）： 1. 15f60e05  Merge branch 'biz-reporter-20260811' into 'master' 分支: master 2. 50741684  Merge branch 'biz-reporter-20260811' into 'test' 分支: test MR记录（按时间倒序）： 1. MR#39 Biz reporter 20260811 状态: closed

**MR#593** (feat: 广告管理平台 拉取BI未配置代理商与产品阶段的账户时提示优化)
- [2026-09-02 11:34] 孙恺(Kai): @yuankangwang 这里写缓存是ok的对吧？业务上可以不需要实时？
- [2026-09-02 11:36] 孙恺(Kai): @yuankangwang 还有flag是不是没加？
- [2026-09-02 11:38] 王远康(Yuankang): 以前缓存6小时  现在我害怕业务不及时刷新  已经变成5分钟了,实时我害怕bi那边顶不住  一次全量账号列表挺多的
- [2026-09-02 11:39] 王远康(Yuankang): 加了  dev 是开的  其他环境是关
- [2026-09-02 11:44] 孙恺(Kai): lgtm

--------------------------------------------------
未活跃成员
--------------------------------------------------

1. 康鑫博(Xinbo) (未活跃)

2. 祁杰(Jacky) (未活跃)

3. 刘松林(Nelson) (未活跃)

4. 解薇(cheryl) (未活跃)

5. 王宁(Willem) (未活跃)

6. 张苒(Ran) (未活跃)

7. 董博(Carl) (未活跃)

8. 朱吉人(Jiren) (未活跃)

--------------------------------------------------
说明：以上内容由 AI 自动生成