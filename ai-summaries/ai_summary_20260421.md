AI 工作总结 · 2026-04-21
==================================================

生成时间：2026-04-22 09:37:07
团队成员数：30
活跃人数：17
未活跃人数：12

--------------------------------------------------
工作总结详情
--------------------------------------------------

1. 徐晨杰(Tito)
   优化达人营销邮箱和负责人信息逻辑，修复相关bug。 【需求：
<br>6931634688([【达人营销】全局邮箱&负责人信息优化-20260331](https://project.feishu.cn/publishing/story/detail/6931634688))
<br>6975440071([【bug】 发布任务里面 查看 通知人帮忙换成最新的格式展示](https://project.feishu.cn/publishing/issue/detail/6975440071))
<br>6975439954([【优化】 移动端 通知人 的格式是有问题的](https://project.feishu.cn/publishing/issue/detail/6975439954))
<br>6948242928([【MirrorSphere】UI自动化功能](https://project.feishu.cn/publishing/story/detail/6948242928))
<br>6935163055([【MSDK管理后台】证书管理二期](https://project.feishu.cn/publishing/story/detail/6935163055))】

2. 曾凡单(Suzy)
   修复投放BI国服订阅通知的bug，回滚消耗录入验证包名使用自归因表。 【需求：
<br>6975680585([【投放bi-国服】订阅通知运行成功后，最近运行状态没有变化，应更新最近一次的推送状态](https://project.feishu.cn/publishing/issue/detail/6975680585))
<br>6952845989([【投放BI国服】后端加接口让新加包名可以更快生效](https://project.feishu.cn/publishing/story/detail/6952845989))】

3. 吴超伟(Chaowei)
   开发自归因反作弊规则，优化相关代码和文档。 【需求：
<br>6952411398([【自归因】反作弊规则探索-特征检测](https://project.feishu.cn/publishing/story/detail/6952411398))
<br>6857843035([【数据】抖音公开舆情数据获取调研](https://project.feishu.cn/publishing/story/detail/6857843035))】

4. 田雪健(Storm)
   修复投放BI消耗返点管理批量导入校验和实时指标露出问题。 【需求：
<br>6964142577([【投放BI】「公共」自归因后处理：消耗返点管理批量导入校验、实时指标露出](https://project.feishu.cn/publishing/story/detail/6964142577))】

5. 康鑫博(Xinbo)
   开发OceanAdsV2账户缓存功能，修复相关bug。 【需求：
<br>6955240991([【国服广告平台】V0.4.0 巨量线上素材接入+批量操作+任务限频](https://project.feishu.cn/publishing/story/detail/6955240991))】

6. 孙恺(Kai)
   支持OneLink解析鸿蒙UserAgent。 【需求：
<br>6956288423([【自归因】OneLink支持鸿蒙（HarmonyOS NEXT）](https://project.feishu.cn/publishing/story/detail/6956288423))】

7. 姜承(JoJo)
   优化国服广告平台功能，修复bug并添加新特性。 【需求：
<br>6952741658([【国服广告平台】V0.3.0 巨量定向包模板和原生锚点模板管理](https://project.feishu.cn/publishing/story/detail/6952741658))】

8. 郑淼(Miao)
   优化MirrorSphere UI自动化功能，合并代码并修改表名。 【需求：
<br>6948242928([【MirrorSphere】UI自动化功能](https://project.feishu.cn/publishing/story/detail/6948242928))】

9. 徐腾飞(Tengfei)
   处理达人营销邮箱和素材信息，修复相关bug。 【需求：
<br>6931634688([【达人营销】全局邮箱&负责人信息优化-20260331](https://project.feishu.cn/publishing/story/detail/6931634688))】

10. 张帆(Mlxg)
   更新MSDK iOS本地推送功能，优化代码结构。 【需求：
<br>6962344010([【MSDK】iOS 本地推送相关功能的中间层更新](https://project.feishu.cn/publishing/story/detail/6962344010))】

11. 孙鹏
   对接国服广告平台锚点模板API。 【需求：
<br>6952741658([【国服广告平台】V0.3.0 巨量定向包模板和原生锚点模板管理](https://project.feishu.cn/publishing/story/detail/6952741658))】

12. 李孔权(Levir)
   优化MSDK管理后台数据接口和注释。 【需求：
<br>6974530193([【MSDK管理后台】stage_id数据下游新增传参](https://project.feishu.cn/publishing/story/detail/6974530193))】

13. 马亮亮(Kuroky)
   发布MSDK本地CocoaPods配置。 【需求：
<br>6973301387([MSDK 本地 CocoaPods 配置发布](https://project.feishu.cn/publishing/story/detail/6973301387))】

14. 王枫荻(Fengdi)
   优化海外广告管理平台上传限流功能。 【需求：
<br>6747401257([【海外】【广告管理平台】TT上传限流优化](https://project.feishu.cn/publishing/story/detail/6747401257))】

15. 田元林(Candy)
   初始化驾驶舱海外数据看板移动端适配。 【需求：
<br>6968610961([【驾驶舱】「海外」数据看板移动端适配 ](https://project.feishu.cn/publishing/story/detail/6968610961))】

16. 李铭骏(Mingjun)
   已review。

17. 王聪(Wilson)
   LGTM。

--------------------------------------------------
MR 评论汇总
--------------------------------------------------

**MR#2082** (/bi/all-apps接口添加stageInfoMap数据)
- [2026-04-21 16:34] 李铭骏(Mingjun): 已review
- [2026-04-21 16:47] 徐腾飞(Tengfei): 这个我记得是已经有同样功能的方法存在的GetAppStageListByAppIDs
- [2026-04-21 18:16] 李孔权(Levir): 这里考虑是防止从mysql查询数据一次性太多，做了一层拦截（考虑到appIds的量级这里暂时先不考虑分页）
- [2026-04-21 18:16] 李孔权(Levir): 简单做了一个限制，防止从mysql查询数据一次性太多

**MR#2125** (m-6964142577:国服消耗返点录入渠道包名验证走自归因录入&国服增加实时指标库展示)
- [2026-04-21 17:07] 曾凡单(Suzy): 看下字段是否要改下？
- [2026-04-21 17:07] 曾凡单(Suzy): LGTM

**MR#2127** (m-6975680585, 修复发送test也更新记录的问题；修复最后一次推送状态更新的bug)
- [2026-04-21 20:17] 田雪健(Storm): LGTM

**MR#41** (m-6956288423 onelink支持解析鸿蒙UserAgent)
- [2026-04-21 16:37] 王聪(Wilson): LGTM

--------------------------------------------------
未活跃成员
--------------------------------------------------

1. 祁杰(Jacky) (未活跃)

2. 万映(leo) (未活跃)

3. 刘松林(Nelson) (未活跃)

4. 解薇(cheryl) (未活跃)

5. 胡海平(Rambo) (未活跃)

6. 杜民民(Dylan) (未活跃)

7. 王宁(Willem) (未活跃)

8. 丁江(Jiang) (未活跃)

9. 张苒(Ran) (未活跃)

10. 董博(Carl) (未活跃)

11. 张芮萍(Ruiping) (未活跃)

12. 朱吉人(Jiren) (未活跃)

--------------------------------------------------
说明：以上内容由 AI 自动生成