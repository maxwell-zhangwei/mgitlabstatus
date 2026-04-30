AI 工作总结 · 2026-04-29
==================================================

生成时间：2026-04-30 09:36:54
团队成员数：31
活跃人数：13
未活跃人数：18

--------------------------------------------------
工作总结详情
--------------------------------------------------

1. 孙恺(Kai)
   修复OneLink和广告渠道ID相关bug。 【需求：
<br>6956288423([【自归因】OneLink支持鸿蒙（HarmonyOS NEXT）](https://project.feishu.cn/publishing/story/detail/6956288423))
<br>6980841317([【投放BI-国服】oenlink的访问判断，user-agent中OpenHarmony  且  <5.0需判断为安卓，现 没有](https://project.feishu.cn/publishing/issue/detail/6980841317))
<br>6980296799([【投放bi-国服】现点击onelink时判断的鸿蒙逻辑与需求不一致](https://project.feishu.cn/publishing/issue/detail/6980296799))
<br>6956977895([【自归因】自归因广告渠道切换使用广告渠道ID](https://project.feishu.cn/publishing/story/detail/6956977895))
<br>6961965390([【自归因】转化回传接入新渠道：摩投云、易推、人人影视](https://project.feishu.cn/publishing/story/detail/6961965390))】

2. 孙鹏
   更新国服广告平台版本，修复图片校验逻辑。 【需求：
<br>6952741658([【国服广告平台】V0.3.0 巨量定向包模板和原生锚点模板管理](https://project.feishu.cn/publishing/story/detail/6952741658))
<br>6979290941([【BUG】游戏图片、顶部头图未做图片大小校验](https://project.feishu.cn/publishing/issue/detail/6979290941))
<br>6961348605([【自归因】支持实时账号口径-页面功能](https://project.feishu.cn/publishing/story/detail/6961348605))】

3. 曾凡单(Suzy)
   优化广告账号接口，更新请求参数。 【需求：
<br>6980724666([【投放bi-海外】新增广告账号时，现渠道有对应的管家账号，现请求接口返回为空。请求参数现未更新为adPlatformUId](https://project.feishu.cn/publishing/issue/detail/6980724666))
<br>6948717467([【投放BI】「海外」管家、广告账户增加新渠道&广告账户唯一id改造](https://project.feishu.cn/publishing/story/detail/6948717467))】

4. 张芮萍(Ruiping)
   优化广告渠道接口，移除adPlatformName，增加adPlatformUId。 【需求：
<br>6948717467([【投放BI】「海外」管家、广告账户增加新渠道&广告账户唯一id改造](https://project.feishu.cn/publishing/story/detail/6948717467))
<br>6961862282([【投放BI】「国服」广告账户批量导入&删除](https://project.feishu.cn/publishing/story/detail/6961862282))】

5. 徐晨杰(Tito)
   优化MirrorSphere测试用例管理功能交互。 【需求：
<br>6976370116([【MirrorSphere】测试用例管理功能](https://project.feishu.cn/publishing/story/detail/6976370116))】

6. 田元林(Candy)
   适配驾驶舱数据看板移动端，修复空数据。 【需求：
<br>6968610961([【驾驶舱】「海外」数据看板移动端适配 ](https://project.feishu.cn/publishing/story/detail/6968610961))】

7. 王枫荻(Fengdi)
   修复驾驶舱数据看板移动端空数据问题。 【需求：
<br>6968610961([【驾驶舱】「海外」数据看板移动端适配 ](https://project.feishu.cn/publishing/story/detail/6968610961))】

8. 田雪健(Storm)
   支持国服实时搜索和搜索信息主体切换。 【需求：
<br>6961348605([【自归因】支持实时账号口径-页面功能](https://project.feishu.cn/publishing/story/detail/6961348605))】

9. 祁杰(Jacky)
   优化驾驶舱卡片魔王项目样式和反馈。 【需求：
<br>6977710521([【驾驶舱】「海外」接入卡片魔王项目](https://project.feishu.cn/publishing/story/detail/6977710521))】

10. 叶明(Ming)
   新增付费用户留存统计字段。 【需求：
<br>6975004045([【投放BI】「海外」增加新指标付费用户留存](https://project.feishu.cn/publishing/story/detail/6975004045))】

11. 杜民民(Dylan)
   【需求：
<br>6962182830([【自归因】归因匹配接入新渠道：摩投云、易推、人人影视](https://project.feishu.cn/publishing/story/detail/6962182830))】

12. 丁江(Jiang)
   移除调试代码，增加字段和查询功能。

13. 王聪(Wilson)
   无具体工作内容记录。

--------------------------------------------------
MR 评论汇总
--------------------------------------------------

**MR#132** (m-6980102814: fix(auth): 收紧 MOA 权限缓存降级)
- [2026-04-29 17:28] 曾凡单(Suzy): LGTM

**MR#2140** (m-6948717467, m-6980724666, 海外管家媒体渠道从新的db表拿；海外广告账户使用 adPlatformUId 替换  adPlatformName 的逻辑)
- [2026-04-29 17:14] 田雪健(Storm): LGTM • publish_platform/auth_service                 提交:   3  MR:  2  Commit评论:  0  MR评论:  0 分支:dev, m-6980102814-fixmoaerr, test (+123 / -12) 提交记录（按时间倒序）： 1. 6a199219  Merge branch 'm-6980102814-fixmoaerr' into 'dev' 分支: dev, test

**MR#43** (m-6980296799-修复一个useragent里带HarmonyOS的错判问题)
- [2026-04-29 11:26] 王聪(Wilson): LGTM

--------------------------------------------------
未活跃成员
--------------------------------------------------

1. 李孔权(Levir) (未活跃)

2. 覃亮(Daniel) (未活跃)

3. 康鑫博(Xinbo) (未活跃)

4. 姜承(JoJo) (未活跃)

5. 张帆(Mlxg) (未活跃)

6. 万映(leo) (未活跃)

7. 刘松林(Nelson) (未活跃)

8. 解薇(cheryl) (未活跃)

9. 马亮亮(Kuroky) (未活跃)

10. 胡海平(Rambo) (未活跃)

11. 郑淼(Miao) (未活跃)

12. 王宁(Willem) (未活跃)

13. 李铭骏(Mingjun) (未活跃)

14. 徐腾飞(Tengfei) (未活跃)

15. 张苒(Ran) (未活跃)

16. 董博(Carl) (未活跃)

17. 吴超伟(Chaowei) (未活跃)

18. 朱吉人(Jiren) (未活跃)

--------------------------------------------------
说明：以上内容由 AI 自动生成