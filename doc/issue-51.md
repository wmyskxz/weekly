这里记录过去一周，我看到的值得分享的东西。

周刊开源（Github：[wmyskxz/weekly](https://github.com/wmyskxz/weekly)），欢迎提交 issue，投稿或推荐精彩内容。

# 题图

![](https://gitee.com/wmyskxz/pic/raw/master/20220214071734.png)

随着北京冬季奥运会的举行，冰壶运动再一次成为人们关注的焦点。而北京冬奥会上使用的冰壶，全部来自苏格兰一个无人居住小岛。这个小岛上独一无二的花岗岩为[冰壶](https://www.bbc.com/zhongwen/simp/uk-60319628 "北京冬奥冰壶揭秘：苏格兰偏僻小岛花岗石的前世与今生")运动提供了最佳的器材。

# 本周讨论：巨无霸汉堡的价值与代价

(参考文案：[@Joel Spolsky](https://www.joelonsoftware.com/2001/01/18/big-macs-vs-the-naked-chef/ "巨无霸汉堡的价值代价"))

![](https://gitee.com/wmyskxz/pic/raw/master/20220213164557.png)

巨无霸汉堡自 1968 年发明以来，之所以长久地畅销，**原因不在于它有多好，而在于它们几乎相同**——无论在什么样的环境下，你都能得到几乎一模一样的汉堡。

另一个秘密是，无论是最聪明的人，还是最愚蠢的人，都能胜任巨无霸的制作——这归功于麦当劳事无巨细的操作手册。

一些聪明人设计的这些规则包括了一系列的针对人类弱点设计的故障保险，比如薯条放在油里太久会响铃，以及各种计时器和傻瓜式操作的烹饪设备。

整个系统的基本假定就是：每个人都会犯一堆错误，但做出来的汉堡是一致的。

![](https://gitee.com/wmyskxz/pic/raw/master/20220213213639.png)

如果有一个电视上的天才厨师，能做出来比麦当劳更好吃的东西，希望能自己开店经营，但是很快就会遇到规模化的问题。

如果考虑聘请和自己也一样优秀的厨师的话，那为什么人家不自己做？如果聘请一些年轻的厨师，但是口味就无法得到保障。

所以，最好的方案还是聘请没什么经验的厨师，然后让他们遵循详细的规则。

但事情并非这么简单，你的厨师总还是有即兴发挥的事情，他们可能要处理非标准化的蔬菜问题，奇怪的口味需求问题等等。所以在麦当劳背后，还有非常多的供应链优化，以至于他们根本不须要有「厨师」技能的人来操作也可以保证口味一致。

所以整个循环概括起来就是：

1. 有些事情需要天赋才能做好；
2. 人才很难扩展；
3. 人们试图扩大规模的方式是让「有天赋的人」为「没有天赋的人」制定规则；
4. 由此产生的产品质量非常低；

故事还有另外一面，**谨防方法论**。虽然方法论可以把每个人提升到及格的水平，但是与此同时也有才华的人发挥——一个有才华的人不会喜欢在麦当劳做汉堡。

所以要明白你是要做麦当劳，还是做一家有特色的餐厅 —— 不同的是互联网和软件让我们交付的能力大有不同。

所以选择是：如果我们雇佣不到好的人，我们就不扩大规模。

# 热点新闻

1、[「马院士」已就位!](http://www.geekpark.net/news/298228 "马斯克：从今天起，请叫我「马院士」")

![](https://gitee.com/wmyskxz/pic/raw/master/20220211150858.png)

2 月 10 日上午，美国国家工程院（National Academy of Engineering，NAE）公布新一期院士名单，特斯拉以及 SpaceX CEO 伊隆·马斯克，正式当选美国国家工程院院士。

---

2、[远程操作机器人](https://www.sohu.com/a/416864728_489960 "健壮的“袋鼠补货员”在日本便利店出没！头长犄角手有吸盘画风奇特")

![](https://gitee.com/wmyskxz/pic/raw/master/20220214062435.png)

Telexistence Inc 是一家位于日本东京的机器人创业公司，致力于开发具有人工智能的远程控制机器人，使人们摆脱空间上的限制。

Telexistence 最近推出了一款名为 Model-T 的新型机器人。在这项试验中，人类“操作员”远程操作机器人，处理商店物品。未来无人超市上货或许可以使用这种方式，而不需要货架管理员跑遍各个超市工作。

![](https://gitee.com/wmyskxz/pic/raw/master/20220214062605.gif)

---

3、[人工智能写的笑话](https://news.ycombinator.com/item?id=30315604 "一个人工智能写的笑话：“一个基本的程序走进了酒吧”")

Google 研究人员最近发表的题为“LaMDA: Language Models for Dialog Applications”的论文，其中有一段用户正在测试 AI 时，让 AI 写一个关于 BASIC 程序的笑话的对话记录，被隐藏在了附录之中，

```text
- User:  Can we write a joke together. I could add a punch line
- LaMDA: We can try. Do you have a starting line of code?
- User:  Line 10: A basic program walked into a bar
- LaMDA: Line 11: Console.Write("and said, ");
- User:  Line 12: Console.Write("what when you forgot a line?")
- LaMDA: Line 13: Console.Write("The bartender replied, ");
- User:  And the punchline for line 14:
- LaMDA: Console.Write("sorry it’s not my fault, I was written by the lowest bidder!")
- User:  lol
- LaMDA: That’s a pretty good joke, wouldn’t you agree?
- User:  Better!
```

---

4、[国内首条「超高速」即将通车，限速 150km/h](https://www.ifanr.com/1470994 "国内首条「超高速」即将通车，限速 150km/h")

![](https://gitee.com/wmyskxz/pic/raw/master/20220214064953.png)

我国第一条「超高速公路」即将建成通车啦，该高速路改建工程为杭州亚运会的配套工程，以宁波市镇海区威海路为起点，终点为杭州市江干区下沙枢纽，全长 161 公里。

基于德国无限速高速公路的标准打造，限制的最高时速为 150km/h。

---

5、[地球内核的秘密](https://finance.sina.com.cn/tech/2022-02-13/doc-ikyakumy5669872.shtml "《自然》：改写教科书！中国科学家揭开地球最深处的秘密")

![](https://gitee.com/wmyskxz/pic/raw/master/20220214065501.png)

教科书告诉我们，由外至内，地球由地壳、地幔和地核这 3 个主要圈层构成，而地球的核心又分为液态外核和**固态的铁镍内核**。

最新发表的《自然》研究，提出了地球内核的新模型：内核并不是普通的固体，而是由固态铁晶格和类似液态的轻元素共同组成的**超离子态**（一种介于固态与液态之间的状态，在行星内部普遍存在。借助计算机模拟，研究团队发现，一些铁-氢、铁-碳和铁-氧复合物可以在内核的高温、高压条件下转变为超离子态）。

*PS：Anyway... 我们的教材可能要随着这次的发现修改了...*


# 文章

1、[谈谈公司对员工的监控](https://coolshell.cn/articles/22157.html "谈谈公司对员工的监控")

![](https://gitee.com/wmyskxz/pic/raw/master/20220212163617.png)

陈皓叔的文章，我比较同意其中的观点：

> 如果你对自己的企业有信心，你就不必担心员工会离开，如果你的企业有问题，你为什么不把心思花在建设自己的企业上来呢？

---

2、[当我们谈论效率的时候，我们在谈论什么](https://sspai.com/post/71159 "当我们谈论效率的时候，我们在谈论什么")

![](https://gitee.com/wmyskxz/pic/raw/master/20220212164220.png)

我对效率的看法始终是：`效率 = 有用功 / 总共`。所以提高效率，换句话说，就是提高自己单位时间内产出的价值。

当我们意识到这一点，那么工具的作用和价值就得以体现。

---

3、[摩卡壶、虹吸壶、法压壶……自己做咖啡到底该提哪壶？](https://www.guokr.com/article/460981 "摩卡壶、虹吸壶、法压壶……自己做咖啡到底该提哪壶？")

![](https://gitee.com/wmyskxz/pic/raw/master/20220212164919.png)

冲泡咖啡喝多了就觉得味儿淡了许多，最近准备入手一台全自动咖啡机使使...

---

4、[UTF-8 的工作原理](https://sethmlarson.dev/blog/utf-8 "UTF-8 如何将“😂”变成“F09F9882”？")（英文）

![](https://gitee.com/wmyskxz/pic/raw/master/20220212165614.png)

UTF-8 是如何将“😂”变成“F09F9882”的？

---

5、[迪士尼电影制作过程](https://disneyanimation.com/process/ "迪士尼电影制作过程")(英文)

![](https://gitee.com/wmyskxz/pic/raw/master/20220212174314.jpeg)

迪士尼官方公布了它们制作动画电影的过程，如果感兴趣可以戳戳。

---

6、[易观分析：2022企业数字化技术应用10大趋势](https://www.infoq.cn/minibook/Q6gNbQVbmvimOxGNPOmX "易观分析：2022企业数字化技术应用10大趋势")

![](https://gitee.com/wmyskxz/pic/raw/master/20220214060856.png)

伴随《“十四五”数字经济发展规划》印发，我国正在迎来焕然一新的数字面貌。

易观分析重磅发布《数字经济全景白皮书》企业数字化技术应用篇，从技术和行业两个视角，预判 2022 年企业数字化技术应用 10 大趋势。

---

7、[ThoughtWorks 徐昊：如何打造高效能团队](https://www.infoq.cn/article/FWFdqHfOPZ7BbJbtzOTx "ThoughtWorks 徐昊：如何打造高效能团队")

![](https://gitee.com/wmyskxz/pic/raw/master/20220214061412.png)

方法论，但并不是“拿来即用”的东西，需要自己理解理解。集中说了两点：

1. 构建知识壁垒，通过交互（分工）提高效率；
2. 基于金字塔结构，分离有效性（Effectiveness）和效率（Efficiency）；

---

8、[北京冬奥会省钱黑科技](https://m.weibo.cn/status/4736420154967787? "北京冬奥会只花了39亿美元？比俄罗斯少了四百多亿是怎么省钱的？“节俭办奥运”的背后展示了未来10年中国科技方向！")（视频）

![](https://gitee.com/wmyskxz/pic/raw/master/20220214062037.png)

北京冬奥会只花了 39 亿美元，比俄罗斯少了四百多亿，这是怎么省钱的？感兴趣的可以戳戳。

---

9、[对生孩子这件事情的思考](https://sspai.com/post/71210 "对生孩子这件事情的思考")

![](https://gitee.com/wmyskxz/pic/raw/master/20220214070611.png)

今年倒是听了身边一些丁克的故事，我们必须承认的是，人对同一件事的认知和反应千差万别，我们首先要做到的就是尊重选择。

总之，关于孩子这件事，发表出来讨论的文章还是比较少的，文章也不仅仅是探讨生孩子，也有人生哲思的讨论。

# 好奇星人

本周暂无；

# 言论

1、

> 做品牌的优秀创始人的思考方式永远是**让喜欢我的人尽可能地更喜欢我，而不是说尽可能地让更多的人知道我**。
>
> 我再表达一次两者的区别，有的人的思考方式是让尽可能多地人知道我，有更多的触达、有更多的新增等等。而有的人的目标是，在喜欢我的这个群体中，尽可能地让这种喜欢的程度更深。

--[E09 孟岩对话黄海：让更多人知道你，还是让爱你的人更爱你](https://www.xiaoyuzhoufm.com/episode/61dbf5b519e8465da2f8f4fd "E09 孟岩对话黄海：让更多人知道你，还是让爱你的人更爱你")

2、

> 在步兵战斗中，只有一种策略：**开火然后移动**（一边扣动扳机，一边向目标移动）。开火迫使敌人低头，这样他就不能向你开火。（这就是士兵喊「掩护我」时的意思。意思是向「向我们的敌人开火，这样他就必须躲避，不能在我跑过这条街时向我开火」）
>
> 你必须每天前进一点。如果你不断前进，不断编写代码并修复错误，那么时间就在您身边。当你的竞争对手向你开火时要小心。他们只是想强迫你忙着对他们的截击做出反应，这时你能继续前进吗？

--[Fire And Motion](https://www.joelonsoftware.com/2002/01/06/fire-and-motion/ "Fire And Motion")（英文）

3、

> 事实上，我发现我喜欢看自传或者人物故事的原因，就是因为在不同的环境里，总有一些人可以做出自己的选择，活成让自己喜悦的模样。
>
> 看到这样的人和故事，就会觉得很美好。

--[孟岩](https://mp.weixin.qq.com/s/qOJ_8doL4wYKEWQn3Qf-1g "再拉法一点")

4、

> 你抗拒走亲戚，可能是因为它让你变得又累又穷。

--[为什么年轻人越来越讨厌走亲戚](https://mp.weixin.qq.com/s/B-jHm4A13i-bxzIjEvyXcg "为什么年轻人越来越讨厌走亲戚")

5、

> 所以，客观上邮件是不方便的，但就是这种不方便反而利于劳动者，
>
> 这是对劳动者私人空间的尊重，
>
> 是对上/下班界限的明晰。

--[为什么国外把邮件当微信一样发？@李小粥](https://www.zhihu.com/question/327715169 "为什么国外把邮件当微信一样发？")

6、

> 我问过我一个很赞的建筑师朋友，一个人到底需要多少平方米的房子才能像个人样儿地住？他说，十二平方米。

--[《有本事》·冯唐](https://book.douban.com/subject/35496147/ "《有本事》·冯唐")


# 订阅

这个周刊每个礼拜一发布，同步更新在[个人博客](https://www.wmyskxz.com/)和[微信公众号](https://weixin.sogou.com/weixin?type=1&s_from=input&query=wmyskxz&ie=utf8&_sug_=n&_sug_type_=&w=01019900&sut=1861&sst0=1612590375262&lkt=8%2C1612590373961%2C1612590375161)

微信搜索"我没有三颗心脏"或者扫描二维码，即可订阅。

![](https://gitee.com/wmyskxz/pic/raw/master/20220109211124.png)

