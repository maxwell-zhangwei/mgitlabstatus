AI 工作总结 · 2026-04-27
==================================================

生成时间：2026-04-28 09:37:14
团队成员数：31
活跃人数：15
未活跃人数：16

--------------------------------------------------
工作总结详情
--------------------------------------------------

1. 祁杰(Jacky)
   修复【投放BI】国服广告账户批量导入错误，更新版本及添加字段。 【需求：
<br>6961862282([【投放BI】「国服」广告账户批量导入&删除](https://project.feishu.cn/publishing/story/detail/6961862282))
<br>6961348605([【自归因】支持实时账号口径-页面功能](https://project.feishu.cn/publishing/story/detail/6961348605))
<br>6328811910([【投放bi】-可视化看板-编辑看板，拖拽右方图表时，出现页面卡住或提示图表不存在](https://project.feishu.cn/publishing/issue/detail/6328811910))】

2. 康鑫博(Xinbo)
   优化【OceanAdsV2】定向包按行政区域划分，解决ubmax campaign问题。 【需求：
<br>6979475420([【优化】定向包按行政区域划分，返回的省的列表数据建议按照首字母排序
[图片]](https://project.feishu.cn/publishing/issue/detail/6979475420))
<br>6955240991([【国服广告平台】V0.4.0 巨量线上素材接入+批量操作+任务限频](https://project.feishu.cn/publishing/story/detail/6955240991))】

3. 田雪健(Storm)
   支持【投放bi】同步APP阶段信息，解决dashboard_service测试阻塞。 【需求：
<br>6974429654([【投放bi】「公共」同步stageid信息](https://project.feishu.cn/publishing/story/detail/6974429654))
<br>6961348605([【自归因】支持实时账号口径-页面功能](https://project.feishu.cn/publishing/story/detail/6961348605))】

4. 杜民民(Dylan)
   接入新渠道摩投云、易推、人人影视，支持模糊匹配ua。 【需求：
<br>6962182830([【自归因】归因匹配接入新渠道：摩投云、易推、人人影视](https://project.feishu.cn/publishing/story/detail/6962182830))
<br>6975289415([【自归因】概率匹配支持IP+UA - 数据处理](https://project.feishu.cn/publishing/story/detail/6975289415))】

5. 张芮萍(Ruiping)
   优化【投放BI】海外管家、广告账户功能，调整字段及统一类型。 【需求：
<br>6948717467([【投放BI】「海外」管家、广告账户增加新渠道&广告账户唯一id改造](https://project.feishu.cn/publishing/story/detail/6948717467))】

6. 曾凡单(Suzy)
   优化【投放BI】海外管家、广告账户功能，调整数据库及逻辑。 【需求：
<br>6948717467([【投放BI】「海外」管家、广告账户增加新渠道&广告账户唯一id改造](https://project.feishu.cn/publishing/story/detail/6948717467))】

7. 徐晨杰(Tito)
   优化【MirrorSphere】测试用例管理功能，增加新功能及交互调整。 【需求：
<br>6976370116([【MirrorSphere】测试用例管理功能](https://project.feishu.cn/publishing/story/detail/6976370116))】

8. 孙鹏
   修复游戏图片裁剪比例问题。 【需求：
<br>6979372681([【BUG】游戏图片剪裁时进行缩放后，尺寸就不是标准的3:5/2:1了](https://project.feishu.cn/publishing/issue/detail/6979372681))】

9. 王枫荻(Fengdi)
   修复和适配【驾驶舱】海外数据看板移动端，修改分组逻辑。 【需求：
<br>6968610961([【驾驶舱】「海外」数据看板移动端适配 ](https://project.feishu.cn/publishing/story/detail/6968610961))】

10. 丁江(Jiang)
   优化【MSDK】支付容灾DB，新增退款干预方法。 【需求：
<br>6955869428([【MSDK】支付容灾DB优化 - 三期](https://project.feishu.cn/publishing/story/detail/6955869428))】

11. 徐腾飞(Tengfei)
   增强MSDK公共组件指标监控，优化消息体大小及需求文档。 【需求：
<br>6977715137([MSDK公共组件增加指标监控](https://project.feishu.cn/publishing/story/detail/6977715137))】

12. 孙恺(Kai)
   新增自归因广告渠道的唯一id。 【需求：
<br>6956977895([【自归因】自归因广告渠道切换使用广告渠道ID](https://project.feishu.cn/publishing/story/detail/6956977895))】

13. 田元林(Candy)
   新增数据看板+数据看板详情。 【需求：
<br>6968610961([【驾驶舱】「海外」数据看板移动端适配 ](https://project.feishu.cn/publishing/story/detail/6968610961))】

14. 郑淼(Miao)
   【需求：
<br>6976370116([【MirrorSphere】测试用例管理功能](https://project.feishu.cn/publishing/story/detail/6976370116))】

15. 王宁(Willem)
   修改ad_platform映射。

--------------------------------------------------
MR 评论汇总
--------------------------------------------------

**MR#2136** (m-6961348605: 国服实时看板支持主体切换)
- [2026-04-27 11:56] 曾凡单(Suzy): LGTM

**MR#2137** (m-6974429654: 支持 updateapp 同步 APP 阶段信息)
- [2026-04-27 15:40] 曾凡单(Suzy): LGTM

**MR#2138** (m-6948717467,  海外管家媒体渠道从新的db表拿；海外广告账户使用 adPlatformUId 替换  adPlatformName 的逻辑)
- [2026-04-27 20:25] 田雪健(Storm): LGTM • publish_platform/nuwa                         提交:   1  MR:  0  Commit评论:  0  MR评论:  0 分支:main 提交记录（按时间倒序）： 1. 93fd0c2a  Merge branch 'm-6957139865-nuwa' into 'main' 分支: main

--------------------------------------------------
未活跃成员
--------------------------------------------------

1. 李孔权(Levir) (未活跃)

2. 覃亮(Daniel) (未活跃)

3. 姜承(JoJo) (未活跃)

4. 张帆(Mlxg) (未活跃)

5. 王聪(Wilson) (未活跃)

6. 万映(leo) (未活跃)

7. 刘松林(Nelson) (未活跃)

8. 解薇(cheryl) (未活跃)

9. 马亮亮(Kuroky) (未活跃)

10. 胡海平(Rambo) (未活跃)

11. 叶明(Ming) (未活跃)

12. 李铭骏(Mingjun) (未活跃)

13. 张苒(Ran) (未活跃)

14. 董博(Carl) (未活跃)

15. 吴超伟(Chaowei) (未活跃)

16. 朱吉人(Jiren) (未活跃)

--------------------------------------------------
说明：以上内容由 AI 自动生成