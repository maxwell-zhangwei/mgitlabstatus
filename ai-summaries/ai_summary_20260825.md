AI 工作总结 · 2026-08-25
==================================================

生成时间：2026-08-26 09:38:31
团队成员数：32
活跃人数：18
未活跃人数：13

--------------------------------------------------
工作总结详情
--------------------------------------------------

1. 孙恺(Kai)
   优化回传规则，增加Oppo requestid。 【需求：
<br>7083870339([【自归因】回传配置-回传规则优化](https://project.feishu.cn/publishing/story/detail/7083870339))
<br>7074806893([【自归因】OPPO转化回传添加request_id参数](https://project.feishu.cn/publishing/story/detail/7074806893))
<br>7078427207([【国服】广告管理平台 直播混投广告组批量追加创意的](https://project.feishu.cn/publishing/story/detail/7078427207))】

2. 张帆(Mlxg)
   优化MSDK接入插件和打包平台，新增Unity集成服务。 【需求：
<br>7062490575([【MSDK接入】MSDK打包平台关联飞书](https://project.feishu.cn/publishing/story/detail/7062490575))
<br>7065301787([【MSDK管理后台】iOS重签包](https://project.feishu.cn/publishing/story/detail/7065301787))】

3. 王枫荻(Fengdi)
   修复推送消息发送中途重启问题。 【需求：
<br>7062059993([【遗留优化】推送消息发送中途，重启pod，服务恢复后，会导致消息重复发送](https://project.feishu.cn/publishing/issue/detail/7062059993))】

4. 万映(leo)
   更新MSDK接入文档，新增推送和广告配置测试文档。 【需求：
<br>7080537853([【MSDK接入】msdk文档静态网页内容搭建](https://project.feishu.cn/publishing/story/detail/7080537853))】

5. 王远康(Yuankang)
   优化素材使用原标题数量截断。 【需求：
<br>7078426899([【国服】广告管理平台-线上素材使用原视频标题时 超10个的拦截优化](https://project.feishu.cn/publishing/story/detail/7078426899))】

6. 徐腾飞(Tengfei)
   优化场景导入API和测试计划导入模块。 【需求：
<br>7090097024([【MirrorSphere】26.09优化需求](https://project.feishu.cn/publishing/story/detail/7090097024))】

7. 解薇(cheryl)
   接入打标服务，优化run_layout_v2。 【需求：
<br>7043811049([【素材农场】接入打标服务 基础流程打通](https://project.feishu.cn/publishing/story/detail/7043811049))】

8. 覃亮(Daniel)
   优化国服广告管理平台日志。 【需求：
<br>7054331904([【国服】广告管理平台 接收巨量SPI广告相关推送](https://project.feishu.cn/publishing/story/detail/7054331904))】

9. 田元林(Candy)
   抽取公共api，优化驾驶舱实时数据移动端。 【需求：
<br>7064756831([【驾驶舱】「海外」实时数据移动端](https://project.feishu.cn/publishing/story/detail/7064756831))】

10. 刘松林(Nelson)
   修复和优化素材农场演示反馈。 【需求：
<br>7070000957([【素材农场】素材农场演示反馈 3期迭代](https://project.feishu.cn/publishing/story/detail/7070000957))】

11. 杜民民(Dylan)
   支持巨量融合方案，处理鸿蒙端问题。 【需求：
<br>7082196874([【自归因】鸿蒙端支持巨量融合方案](https://project.feishu.cn/publishing/story/detail/7082196874))】

12. 曾凡单(Suzy)
   添加投放BI预警管理API。 【需求：
<br>7067251698([【投放BI】「国服」预警管理1.0](https://project.feishu.cn/publishing/story/detail/7067251698))】

13. 胡海平(Rambo)
   优化客服系统，实现历史客诉数据持久化。 【需求：
<br>7067524588([客服系统搭建-m1 ](https://project.feishu.cn/publishing/story/detail/7067524588))】

14. 李铭骏(Mingjun)
   优化规则和文档，推进BASEM1ENVDBISOLATION项目。

15. 丁江(Jiang)
   修复和更新报告查询、编写viewbizreport统计。

16. 徐晨杰(Tito)
   更新SDK版本和修复样式问题，优化连接_id携带。

17. 马亮亮(Kuroky)
   优化图片预览和文本URL链接渲染。

18. 郑淼(Miao)
   更新README.md。

--------------------------------------------------
MR 评论汇总
--------------------------------------------------

**MR#58** (feat(attachment): object_key 规则修订——环境段前缀 + 日期按日粒度 (IL-M1-S17A-OBJECTKEY-ENV))
- [2026-08-25 16:42] 李铭骏(Mingjun): c.Env从何获取 • msdk/rispari/server/admin-gateway             提交:  24  MR:  7  Commit评论:  0  MR评论:  0 分支:chore/retro-improvements-sync, feature/AG-2-prune, feature/AG-3-govern, feature/AG-4-ATTACH-RESOURCE-URL-attach-resource-url, feature/AG-5-ORIGIN-CONN-agent-origin-conn, feature/BASE-GS-DOCS-SYNC-claude, fix/AG-3-ledger-format, milestone/M1 (+1,866 / -41,763) 提交记录（按时间倒序）：

**MR#59** (fix(ticket): 满意度提交/过期迁移后回写卡片状态，修复补拉恒显待评价 (IL-M1-FIX-SAT-CARD-SYNC))
- [2026-08-25 17:15] 李铭骏(Mingjun): 这里两个repo是同一个吗？

**MR#62** (refactor(main): IL-M1-FIX-MAIN-SPLIT main.go 600 行越线拆分——收敛启动骨架 + 装配面按职责拆分三文件)
- [2026-08-25 19:10] 李铭骏(Mingjun): 这几个wiring_xxx.go文件可以放在独立的目录下吗？而不是平铺在根目录

--------------------------------------------------
未活跃成员
--------------------------------------------------

1. 李孔权(Levir) (未活跃)

2. 康鑫博(Xinbo) (未活跃)

3. 姜承(JoJo) (未活跃)

4. 祁杰(Jacky) (未活跃)

5. 王聪(Wilson) (未活跃)

6. 孙鹏 (未活跃)

7. 田雪健(Storm) (未活跃)

8. 王宁(Willem) (未活跃)

9. 张苒(Ran) (未活跃)

10. 董博(Carl) (未活跃)

11. 吴超伟(Chaowei) (未活跃)

12. 张芮萍(Ruiping) (未活跃)

13. 朱吉人(Jiren) (未活跃)

--------------------------------------------------
说明：以上内容由 AI 自动生成