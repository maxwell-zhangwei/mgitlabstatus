AI 工作总结 · 2026-04-13
==================================================

生成时间：2026-04-14 11:23:01
团队成员数：30
活跃人数：18
未活跃人数：12

--------------------------------------------------
工作总结详情
--------------------------------------------------

1. 康鑫博(Xinbo)
   修复OceanAdsV2多个bug 【需求：
<br>6956216955([【bug】多账户时，分账户选择原生锚点，generate接口返回的数据有问题，所有账号的原生锚点都一样](https://project.feishu.cn/publishing/issue/detail/6956216955))
<br>6956318943([【bug】广告内包含多个创意组时，部分创意组失败广告状态应该判断为失败](https://project.feishu.cn/publishing/issue/detail/6956318943))
<br>6956293792([【bug】多账户创建广告会报错：资产校验失败](https://project.feishu.cn/publishing/issue/detail/6956293792))
<br>6954390065([【bug】巨量拉回的项目/广告数据问题汇总（打包）该问题遗留一个P2的问题：巨量拉回的转化目标映射成本地的](https://project.feishu.cn/publishing/issue/detail/6954390065))】

2. 徐晨杰(Tito)
   达人营销社媒发布优化 【需求：
<br>6928888567([【达人营销】社媒发布优化-20260326](https://project.feishu.cn/publishing/story/detail/6928888567))
<br>6935163055([【MSDK管理后台】证书管理二期](https://project.feishu.cn/publishing/story/detail/6935163055))
<br>6955860397([移动端编辑和添加时没传主页类型字段](https://project.feishu.cn/publishing/issue/detail/6955860397))】

3. 姜承(JoJo)
   多账户选择抽屉切Tab优化 【需求：
<br>6956620491([【bug】多个账户下，原生锚点选择器，初始进入选择抽屉时，在账户之间切换会清空账户的已选内容](https://project.feishu.cn/publishing/issue/detail/6956620491))
<br>6956057639([【bug】在配置了项目出价的策略的基础上修改，修改为不配出价，生成预览/保存策略时，项目bid依然会传之前的出价值](https://project.feishu.cn/publishing/issue/detail/6956057639))】

4. 郑淼(Miao)
   MirrorSphere UI自动化功能优化及AIChat 1.0功能开发 【需求：
<br>6948242928([【MirrorSphere】UI自动化功能](https://project.feishu.cn/publishing/story/detail/6948242928))
<br>6950014485([【MirrorSphere】AIChat 1.0功能](https://project.feishu.cn/publishing/story/detail/6950014485))】

5. 丁江(Jiang)
   MSDK管理后台证书管理二期及支付容灾DB优化 【需求：
<br>6935163055([【MSDK管理后台】证书管理二期](https://project.feishu.cn/publishing/story/detail/6935163055))
<br>6955869428([【MSDK】支付容灾DB优化 - 三期](https://project.feishu.cn/publishing/story/detail/6955869428))】

6. 吴超伟(Chaowei)
   FB&INS爬虫开发及爬虫重构 【需求：
<br>6955502693([爬虫重构-test](https://project.feishu.cn/publishing/story/detail/6955502693))
<br>6930690418([【数据】FB&INS提供帖子URL获取评论并分析](https://project.feishu.cn/publishing/story/detail/6930690418))】

7. 李铭骏(Mingjun)
   文档更新及【MSDK】Age Gate 策略功能开发 【需求：
<br>6928766508([【MSDK】Age Gate 策略功能](https://project.feishu.cn/publishing/story/detail/6928766508))】

8. 徐腾飞(Tengfei)
   达人营销社媒发布优化及权限校验 【需求：
<br>6928888567([【达人营销】社媒发布优化-20260326](https://project.feishu.cn/publishing/story/detail/6928888567))】

9. 祁杰(Jacky)
   设置默认周期切换通知类型 【需求：
<br>6924113603([【海外】【投放BI】订阅管理增加多时段推送功能](https://project.feishu.cn/publishing/story/detail/6924113603))】

10. 孙恺(Kai)
   自归因转化回传优化需求 【需求：
<br>6935204012([【自归因】转化回传优化需求-20260331](https://project.feishu.cn/publishing/story/detail/6935204012))】

11. 曾凡单(Suzy)
   【投放BI国服】订阅功能国服开放 【需求：
<br>6935185996([【投放BI国服】订阅功能国服开放](https://project.feishu.cn/publishing/story/detail/6935185996))】

12. 王宁(Willem)
   数据】steam数据拉取调研 【需求：
<br>6925809214([【数据】steam数据拉取调研](https://project.feishu.cn/publishing/story/detail/6925809214))】

13. 董博(Carl)
   【需求：
<br>6638908378([【投放BI国际服】实时数据对接moba日志平台](https://project.feishu.cn/publishing/story/detail/6638908378))】

14. 叶明(Ming)
   【需求：
<br>6935218843([【数据】驾驶舱消耗数据切换至核减后字段](https://project.feishu.cn/publishing/story/detail/6935218843))】

15. 杜民民(Dylan)
   自归因优化 【需求：
<br>6954318202([自归因优化](https://project.feishu.cn/publishing/story/detail/6954318202))】

16. 刘松林(Nelson)
   videozhparserv2及unified generator

17. 孙鹏
   版本更新及任务详情优化

18. 王聪(Wilson)
   LGTM

--------------------------------------------------
MR 评论汇总
--------------------------------------------------

**MR#2345** (Opt/publish m 6928888567)
- [2026-04-13T03:09:39.648Z] 郑淼(Miao): UT的要求在过往的kol review已经提过很多次了，这次改动的代码过往的UT都能覆盖吗？这么多变更的文件不需要新增UT？
- [2026-04-13T04:16:34.224Z] 郑淼(Miao): 这个break的位置有问题吧

**MR#464** (feat：dev steam channels m-6925809214)
- [2026-04-13T09:38:23.271Z] 王聪(Wilson): LGTM

--------------------------------------------------
未活跃成员
--------------------------------------------------

1. 李孔权(Levir) (未活跃)

2. 张帆(Mlxg) (未活跃)

3. 王枫荻(Fengdi) (未活跃)

4. 万映(leo) (未活跃)

5. 解薇(cheryl) (未活跃)

6. 马亮亮(Kuroky) (未活跃)

7. 胡海平(Rambo) (未活跃)

8. 田雪健(Storm) (未活跃)

9. 田元林(Candy) (未活跃)

10. 张苒(Ran) (未活跃)

11. 张芮萍(Ruiping) (未活跃)

12. 朱吉人(Jiren) (未活跃)

--------------------------------------------------
说明：以上内容由 AI 自动生成