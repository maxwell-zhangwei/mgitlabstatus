AI 工作总结 · 2026-04-14
==================================================

生成时间：2026-04-15 09:36:49
团队成员数：30
活跃人数：16
未活跃人数：13

--------------------------------------------------
工作总结详情
--------------------------------------------------

1. 孙鹏
   修复和优化行动号召、产品卖点及预算策略逻辑，提交 6 次。 【需求：
<br>6957160987([【优化】行动号召、产品卖点，目前只有后端预览时拦截字符长度，前端建议也改一下输入限制](https://project.feishu.cn/publishing/issue/detail/6957160987))
<br>6861556707([【国服广告平台】巨量第一版第2期-主流程部分](https://project.feishu.cn/publishing/story/detail/6861556707))
<br>6956057639([【bug】在配置了项目出价的策略的基础上修改，修改为不配出价，生成预览/保存策略时，项目bid依然会传之前的出价值](https://project.feishu.cn/publishing/issue/detail/6956057639))】

2. 康鑫博(Xinbo)
   修复 OceanAdsV2 数据同步和配置问题，提交 10 次。 【需求：
<br>6956561087([【bug】（已使用临时方案修复，后续还需要考虑长期方案）巨量拉回的项目，不返回应用平台数据platformType，会导致可以同时在已有的安卓和ios项目下创建广告](https://project.feishu.cn/publishing/issue/detail/6956561087))
<br>6956927871([【bug】（只有pre有问题）从策略创建广告(策略中的enabledAnchor=false)，创建完成后，从任务创建，策略中的enabledAnchor变为了true](https://project.feishu.cn/publishing/issue/detail/6956927871))】

3. 姜承(JoJo)
   修复 ProjectSelectDrawer 和加载规则信息问题，提交 3 次。 【需求：
<br>6961932652([【优化】选择已有项目时，只要之前有选择过项目，就会记录项目的各个字段值，导致即使再取消选择，也不会清空已选，也无法再选择其他字段值的项目了](https://project.feishu.cn/publishing/issue/detail/6961932652))
<br>6960986573([【bug】选择已有项目的策略，进行项目配置时，需要切到包含已选项目的那一页时，顶部信息才能加载出来](https://project.feishu.cn/publishing/issue/detail/6960986573))】

4. 郑淼(Miao)
   优化 MirrorSphere UI 自动化和 AIChat 功能，提交 6 次。 【需求：
<br>6948242928([【MirrorSphere】UI自动化功能](https://project.feishu.cn/publishing/story/detail/6948242928))
<br>6950014485([【MirrorSphere】AIChat 1.0功能](https://project.feishu.cn/publishing/story/detail/6950014485))】

5. 徐晨杰(Tito)
   优化 MSDK 管理后台功能，提交 4 次。 【需求：
<br>6872145972([【MSDK管理后台】新增项目stage_id](https://project.feishu.cn/publishing/story/detail/6872145972))
<br>6935163055([【MSDK管理后台】证书管理二期](https://project.feishu.cn/publishing/story/detail/6935163055))】

6. 马亮亮(Kuroky)
   优化 MSDK Age Gate 策略功能，提交 10 次。 【需求：
<br>6928766508([【MSDK】Age Gate 策略功能](https://project.feishu.cn/publishing/story/detail/6928766508))】

7. 胡海平(Rambo)
   优化 MSDK Age Gate 策略功能，提交 3 次。 【需求：
<br>6928766508([【MSDK】Age Gate 策略功能](https://project.feishu.cn/publishing/story/detail/6928766508))】

8. 曾凡单(Suzy)
   优化海外投放BI订阅管理功能，提交 4 次。 【需求：
<br>6924113603([【海外】【投放BI】订阅管理增加多时段推送功能](https://project.feishu.cn/publishing/story/detail/6924113603))】

9. 杜民民(Dylan)
   验证概率匹配验证归因效果，提交 1 次。 【需求：
<br>6934722734([【自归因】概率匹配验证「IP+UA和IP」归因效果](https://project.feishu.cn/publishing/story/detail/6934722734))】

10. 张芮萍(Ruiping)
   优化投放BI国服后端接口，提交 2 次。 【需求：
<br>6952845989([【投放BI国服】后端加接口让新加包名可以更快生效](https://project.feishu.cn/publishing/story/detail/6952845989))】

11. 李孔权(Levir)
   优化 MSDK 推送功能，提交 5 次。 【需求：
<br>6948676079([【MSDK管理后台】推送功能优化_260408](https://project.feishu.cn/publishing/story/detail/6948676079))】

12. 孙恺(Kai)
   更新自归因转化回传优化需求，提交 1 次。 【需求：
<br>6935204012([【自归因】转化回传优化需求-20260331](https://project.feishu.cn/publishing/story/detail/6935204012))】

13. 徐腾飞(Tengfei)
   优化达人营销社媒发布功能，提交 7 次。 【需求：
<br>6928888567([【达人营销】社媒发布优化-20260326](https://project.feishu.cn/publishing/story/detail/6928888567))】

14. 吴超伟(Chaowei)
   修复爬虫重构test相关脚本，提交 1 次。 【需求：
<br>6955502693([爬虫重构-test(用于代码整理)](https://project.feishu.cn/publishing/story/detail/6955502693))】

15. 田雪健(Storm)
   无提交记录，MR 评论 LGTM。

16. 李铭骏(Mingjun)
   更新文档，提交 1 次。

--------------------------------------------------
MR 评论汇总
--------------------------------------------------

**MR#2111** (m-6924113603, cn-subscription：优化订阅多时段定时任务的加载，每次刷新加载最近的两次任务)
- [2026-04-14 15:30] 田雪健(Storm): LGTM

--------------------------------------------------
未活跃成员
--------------------------------------------------

1. 祁杰(Jacky) (未活跃)

2. 张帆(Mlxg) (未活跃)

3. 王聪(Wilson) (未活跃)

4. 王枫荻(Fengdi) (未活跃)

5. 万映(leo) (未活跃)

6. 刘松林(Nelson) (未活跃)

7. 解薇(cheryl) (未活跃)

8. 田元林(Candy) (未活跃)

9. 王宁(Willem) (未活跃)

10. 丁江(Jiang) (未活跃)

11. 张苒(Ran) (未活跃)

12. 董博(Carl) (未活跃)

13. 朱吉人(Jiren) (未活跃)

--------------------------------------------------
说明：以上内容由 AI 自动生成