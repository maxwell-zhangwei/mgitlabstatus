AI 工作总结 · 2026-04-23
==================================================

生成时间：2026-04-24 09:37:11
团队成员数：31
活跃人数：18
未活跃人数：13

--------------------------------------------------
工作总结详情
--------------------------------------------------

1. 张芮萍(Ruiping)
   修复指标使用不同数据集问题，修改配置。 【需求：
<br>6964142577([【投放BI】「公共」自归因后处理：消耗返点管理批量导入校验、实时指标露出](https://project.feishu.cn/publishing/story/detail/6964142577))
<br>6948717467([【投放BI】「海外」管家、广告账户增加新渠道&广告账户唯一id改造](https://project.feishu.cn/publishing/story/detail/6948717467))】

2. 郑淼(Miao)
   增强MirrorSphere测试用例管理功能，新增标签和字段。 【需求：
<br>6950014485([【MirrorSphere】AIChat 1.0功能](https://project.feishu.cn/publishing/story/detail/6950014485))
<br>6976370116([【MirrorSphere】测试用例管理功能](https://project.feishu.cn/publishing/story/detail/6976370116))】

3. 张帆(Mlxg)
   更新MSDK iOS本地推送中间层，切换源并接入路由。 【需求：
<br>6962344010([【MSDK】iOS 本地推送相关功能的中间层更新](https://project.feishu.cn/publishing/story/detail/6962344010))
<br>6928766508([【MSDK】Age Gate 策略功能](https://project.feishu.cn/publishing/story/detail/6928766508))】

4. 康鑫博(Xinbo)
   改进国服广告平台功能，接入巨量素材，增加日志记录。 【需求：
<br>6955240991([【国服广告平台】V0.4.0 巨量线上素材接入+批量操作+任务限频](https://project.feishu.cn/publishing/story/detail/6955240991))】

5. 曾凡单(Suzy)
   优化广告账户功能，调整返回为数组，增加新渠道。 【需求：
<br>6948717467([【投放BI】「海外」管家、广告账户增加新渠道&广告账户唯一id改造](https://project.feishu.cn/publishing/story/detail/6948717467))】

6. 孙鹏
   调整国服广告平台模板管理，优化视频预览字段和流程。 【需求：
<br>6952741658([【国服广告平台】V0.3.0 巨量定向包模板和原生锚点模板管理](https://project.feishu.cn/publishing/story/detail/6952741658))】

7. 姜承(JoJo)
   优化国服广告平台模板管理，调整分页和配置。 【需求：
<br>6952741658([【国服广告平台】V0.3.0 巨量定向包模板和原生锚点模板管理](https://project.feishu.cn/publishing/story/detail/6952741658))】

8. 徐晨杰(Tito)
   调整MirrorSphere测试用例管理模块设置目录。 【需求：
<br>6976370116([【MirrorSphere】测试用例管理功能](https://project.feishu.cn/publishing/story/detail/6976370116))】

9. 孙恺(Kai)
   接入摩投云和渠道单元测试，支持新渠道转化回传。 【需求：
<br>6961965390([【自归因】转化回传接入新渠道：摩投云、易推、人人影视](https://project.feishu.cn/publishing/story/detail/6961965390))】

10. 田雪健(Storm)
   完善国服广告账户批量导入功能，修正文件路径和表头。 【需求：
<br>6961862282([【投放BI】「国服」广告账户批量导入&删除](https://project.feishu.cn/publishing/story/detail/6961862282))】

11. 祁杰(Jacky)
   修复广告账户批量操作功能，实现批量导入和删除。 【需求：
<br>6961862282([【投放BI】「国服」广告账户批量导入&删除](https://project.feishu.cn/publishing/story/detail/6961862282))】

12. 解薇(cheryl)
   纯标签生成prompt，跟进素材打标跟进单。 【需求：
<br>6953887362([【AI素材农场】图片和视频素材打标 跟进单](https://project.feishu.cn/publishing/story/detail/6953887362))】

13. 王枫荻(Fengdi)
   适配海外数据看板移动端，兼容接口和保存筛选项。 【需求：
<br>6968610961([【驾驶舱】「海外」数据看板移动端适配 ](https://project.feishu.cn/publishing/story/detail/6968610961))】

14. 徐腾飞(Tengfei)
   增强MSDK公共组件指标监控，修复nil输入防御。 【需求：
<br>6977715137([MSDK公共组件增加指标监控](https://project.feishu.cn/publishing/story/detail/6977715137))】

15. 田元林(Candy)
   适配海外数据看板移动端，增加项目明细。 【需求：
<br>6968610961([【驾驶舱】「海外」数据看板移动端适配 ](https://project.feishu.cn/publishing/story/detail/6968610961))】

16. 杜民民(Dylan)
   合并flink17到主分支。 【需求：
<br>6977929077([flink17合并到主分支](https://project.feishu.cn/publishing/story/detail/6977929077))】

17. 张苒(Ran)
   调整模块设置目录，修改名称。

18. 马亮亮(Kuroky)
   完成工作，无具体总结。

--------------------------------------------------
MR 评论汇总
--------------------------------------------------

**MR#2129** (m-6961862282: feat(aam): 增加国服广告账户批量导入基础能力)
- [2026-04-23 16:24] 曾凡单(Suzy): 循环调用db，建议调整下哈 • publish_platform/ad_bi/rta                    提交:   1  MR:  0  Commit评论:  0  MR评论:  0 分支:suzyzeng/encrypt_conf (+1 / -7) 提交记录（按时间倒序）： 1. e31842a2  Revert "m-6948717467, 加密解密类型调整到 conf 中" 分支: suzyzeng/encrypt_conf
- [2026-04-23 16:24] 曾凡单(Suzy): 新增的函数，会加上已经发布的 flag
- [2026-04-23 17:40] 曾凡单(Suzy): 在 单广告账户的拉取逻辑中，命名上使用了 batch，建议调整下哈
- [2026-04-23 17:40] 曾凡单(Suzy): 这里是否需要 tolowercase(trimmed) 再对比？
- [2026-04-23 17:40] 曾凡单(Suzy): ditto
- [2026-04-23 17:40] 曾凡单(Suzy): GetValidCnAutoCostChannelMap 生成的时候为 adPlatformUid => xxx， 对比的时候使用的为 adPlatformName => xxx， 需要确认下哈
- [2026-04-23 17:40] 曾凡单(Suzy): 新增文件中这里是不是可以不需要flag
- [2026-04-23 17:40] 曾凡单(Suzy): 在单条记录逻辑中，命名中使用了 batch，可以看看哈
- [2026-04-23 17:40] 曾凡单(Suzy): 命名方式，ditto
- [2026-04-23 17:40] 曾凡单(Suzy): 命名 ditto
- [2026-04-23 17:40] 曾凡单(Suzy): 命名，ditto
- [2026-04-23 18:02] 曾凡单(Suzy): LGTM

**MR#2130** (m-6948717467, add interface  getaminfomap)
- [2026-04-23 20:30] 田雪健(Storm): LGTM

**MR#2133** (m-6961862282:返点上传路径补上渠道校验)
- [2026-04-23 20:04] 曾凡单(Suzy): LGTM

**MR#3** (m-6962344010)
- [2026-04-23 17:32] 马亮亮(Kuroky): done

--------------------------------------------------
未活跃成员
--------------------------------------------------

1. 李孔权(Levir) (未活跃)

2. 覃亮(Daniel) (未活跃)

3. 王聪(Wilson) (未活跃)

4. 万映(leo) (未活跃)

5. 刘松林(Nelson) (未活跃)

6. 胡海平(Rambo) (未活跃)

7. 叶明(Ming) (未活跃)

8. 王宁(Willem) (未活跃)

9. 李铭骏(Mingjun) (未活跃)

10. 丁江(Jiang) (未活跃)

11. 董博(Carl) (未活跃)

12. 吴超伟(Chaowei) (未活跃)

13. 朱吉人(Jiren) (未活跃)

--------------------------------------------------
说明：以上内容由 AI 自动生成