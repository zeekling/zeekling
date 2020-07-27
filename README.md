### Hey 👋, I'm [Zeek Ling](https://www/zeekling.cn)! 
![Github Stats](https://github-readme-stats.vercel.app/api?username=zeekling&show_icons=true) 
### 我在[小令童鞋](https://www/zeekling.cn)的近期动态

⭐️ Star [个人主页](https://github.com/zeekling/zeekling) 后会自动更新，最近更新时间：`2020-07-27 23:18:21`

📝 帖子 &nbsp; 💬 评论 &nbsp; 🗣 回帖 &nbsp; 🌙 清月 &nbsp; 👨‍💻 用户 &nbsp; 🏷️ 标签 &nbsp; ⭐️ 关注 &nbsp; 👍 赞同 &nbsp; 💗 感谢 &nbsp; 💰 打赏 &nbsp; 🗃 收藏<p align="center"><img alt="小令童鞋" src="https://img.zeekling.cn/images/2020/02/23/logo.th.png"></p><h2 align="center">
小令童鞋
</h2>

<h4 align="center">梅干菜你个小酥饼哦。</h4>
<p align="center"><a title="小令童鞋" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/last-commit/zeekling/zeekling.svg?style=flat-square&color=FF9900"></a>
<a title="GitHub repo size in bytes" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/repo-size/zeekling/zeekling.svg?style=flat-square"></a>
<a title="Hits" target="_blank" href="https://github.com/zeekling/hits"><img src="https://hits.b3log.org/zeekling/zeekling.svg"></a></p>

### 最新

* [自动跟新最新博客到github主页](https://www.zeekling.cn/articles/2020/07/26/1595773591724.html) 
 > <p>最近github可以显示类似于主页的东西了，所以打算将自己最新的博客推送到github主页。</p>
<p>我的github主页:<a href="https://github.com/zeekling" target="_blank">zeekling</a></p>
* [Redis 慢查询分析](https://www.zeekling.cn/articles/2020/07/23/1595493094855.html) 
 > <p>在慢查询的定义中，统计比较慢的时间段指的是<strong>命令执行</strong>这个步骤。没有慢查询，并不表示客户端没有超时问题，有可能网络传输有延迟，也有可能排队的命令比较多。</p>
<p>因为Redis中命令执行的排队机制，慢查询会导致其他命令的级联阻塞，所以当客户端出现请求超时的时候，需要检查该时间点是否有慢查询，从而分析出由于慢查询导致的命令级联阻塞。</p>
* [Redis Sentinel哨兵机制](https://www.zeekling.cn/articles/2020/07/21/1595343778998.html) 
 > <p>Redis的哨兵(sentinel) 系统用于管理多个 Redis 服务器,该系统执行以下三个任务:</p>
<p><strong>监控(Monitoring):</strong> 哨兵(sentinel) 会不断地检查你的Master和Slave是否运作正常。</p>
<p><strong>提醒(Notification):</strong> 当被监控的某个 Redis出现问题时, 哨兵(sentinel) 可以通过 API 向管理员或者其他应用程序发送通知。</p>
<p><strong>自动故障迁移(Automatic failover):</strong> 当一个Master不能正常工作时，哨兵(sentinel) 会开始一次自动故障迁移操作,它会将失效Master的其中一个Slave升级为新的Master, 并让失效Master的其他Slave改为复制新的Master; 当客户端试图连接失效的Master时,集群也会向客户端返回新Master的地址,使得集群可以使用Master代替失效Master。</p>
* [Redis 集群详解](https://www.zeekling.cn/articles/2020/07/21/1595342026052.html) 
 > <p>Redis Cluster 即 Redis 集群，是 Redis 官方在 3.0 版本推出的一套分布式存储方案。完全去中心化，由多个节点组成，所有节点彼此互联。Redis 客户端可以直接连接任何一节点获取集群中的键值对，不需要中间代理，如果该节点不存在用户所指定的键值，其内部会自动把客户端重定向到键值所在的节点。</p>
<p>Redis 集群是一个网状结构，每个节点都通过 TCP 连接跟其他每个节点连接。在一个有 N 个节点的集群中，每个节点都有 N-1 个流出的 TCP 连接，和 N-1 个流入的连接，这些 TCP 连接会永久保持。</p>
* [理解Redis的内存](https://www.zeekling.cn/articles/2020/07/04/1593860561539.html) 
 > <p>Redis 是一种内存数据库，将数据保存在内存中，读写效率要比传统的将数据保存在磁盘上的数据库要快很多。所以，监控 Redis 的内存消耗并了解 Redis 内存模型对高效并长期稳定使用 Redis 至关重要。</p>
* [机器学习知识点总结(长期更新)](https://www.zeekling.cn/articles/2019/08/14/1565788128215.html) 
 > <p>主要是为了列个机器学习相关的提纲,方便对已经学过的知识进行整理,相同的知识点,每次或者每个阶段都会有不同的想法,而我需要做的就是把自己的想法写下来.</p>
* [About Me](https://www.zeekling.cn/aboutMe.html) 
 > <p>本站主要是讲述一个自闭的二逼青年如何自救的一个过程，是一个消费大把大把青春的地方。</p>
* [2020年红河谷游玩](https://www.zeekling.cn/articles/2020/06/06/1591450599075.html) 
 > <p>2020.06.06日，部门组织去红河谷景区游玩，由于我刚来到西安，也没有怎么出去玩，所以就报了名，参加了红河谷的团建。<br>
玩了一天，跑了好多个景点，感觉不太亏。</p>
* [Kafka API操作实践](https://www.zeekling.cn/articles/2020/05/17/1589721212901.html) 
 > <p>  Kafka的Producer发送消息采用的是<strong>异步发送</strong>的方式。在消息发送的过程中，涉及到了<strong>两个线程——main线程和Sender线程</strong>，以及<strong>一个线程共享变量——RecordAccumulator</strong>。main线程将消息发送给RecordAccumulator，Sender线程不断从RecordAccumulator中拉取消息发送到Kafka broker。<br>
Consumer消费数据时的可靠性是很容易保证的，因为数据在Kafka中是持久化的，故不用担心数据丢失问题。<br>
  由于consumer在消费过程中可能会出现断电宕机等故障，consumer恢复后，需要从故障前的位置的继续消费，所以consumer需要实时记录自己消费到了哪个offset，以便故障恢复后继续消费。<br>
  所以offset的维护是Consumer消费数据是必须考虑的问题。</p>
* [Redis数据清理详解](https://www.zeekling.cn/articles/2020/06/22/1592922698436.html) 
 > <p>Redis常用的删除策略有以下三种：</p>
<ul>
<li>被动删除（惰性删除）：当读/写一个已经过期的Key时，会触发惰性删除策略，直接删除掉这个Key;</li>
<li>主动删除（定期删除）：Redis会定期巡检，来清理过期Key；</li>
<li>当内存达到maxmemory配置时候，会触发Key的删除操作；</li>
</ul>
<p>另外，还有一种基于触发器的删除策略，因为对Redis压力太大，一般没人使用。</p>
* [Java 中使用Redis 简单操作](https://www.zeekling.cn/articles/2020/06/22/1592757637089.html) 
 > <p>换了工作之后在华为搞FusionInsight的redis组件，复习下redis相关的知识。从简单的数据操作开始。</p>
* [环材化生劝退计划](https://www.zeekling.cn/articles/2020/06/17/1592323471534.html) 
 > <p></p><h1 align="center">环材化生劝退计划</h1>
<p align="center">劝退一人胜发七篇 CNS</p>
<p></p>
* [Git 命令详解](https://www.zeekling.cn/articles/2019/12/01/1575184426144.html) 
 > <p>主要记录自己平时使用的 Git 命令，方便记忆和查找..</p>
* [人生第一次](https://www.zeekling.cn/articles/2020/03/22/1584880355664.html) 
 > <p>洞察人间凡事，体味人生百态。央视网系列人文纪录片《人生第一次》旨在通过蹲守拍摄，观察不同人群在人生重要节点的“第一次”：第一次上学、第一次上班、第一次走进军营，许多“第一次”串联起我们人生的重要节点，“初来乍到，请多关照”。</p>
* [bolo 博客接入又拍云图床](https://www.zeekling.cn/articles/2020/06/09/1591638203577.html) 
 > <p>我之前博客里面的图片都是用了自己搭建的<a href="https://img.zeekling.cn/" target="_blank">相册</a>里面的，但是毕竟不太方便。并且最近正在搞又拍云的cdn。就顺手把图床这个是也搞定了吧。</p>
* [博客接入又拍云cdn](https://www.zeekling.cn/articles/2020/06/07/1591520906274.html) 
 > <p>由于本人腾讯云服务器的是按照流量收费的，最近网站流量跑的比较快，所以打算接入cdn，把图片缓存下来，减少流量直接打到服务器上面。</p>
* [Kafka深入解析](https://www.zeekling.cn/articles/2020/05/24/1590327441358.html) 
 > <p>Kafka中消息是以topic进行分类的，生产者生产消息，消费者消费消息，都是面向topic的。<br>
topic是逻辑上的概念，而partition是物理上的概念，每个partition对应于一个log文件，该log文件中存储的就是producer生产的数据。Producer生产的数据会被不断追加到该log文件末端，且每条数据都有自己的offset。消费者组中的每个消费者，都会实时记录自己消费到了哪个offset，以便出错恢复时，从上次的位置继续消费。</p>
* [Kafka概述](https://www.zeekling.cn/articles/2020/05/24/1590324636321.html) 
 > <p>Kafka是<strong>一个分布式的基于发布/订阅模式的消息队列</strong>，主要应用于大数据实时处理领域。</p>
* [白蛇缘起](https://www.zeekling.cn/articles/2019/07/14/1563077032010.html) 
 > <p>白蛇缘起，一部国漫的巅峰之作的代表。</p>
* [决策树详解](https://www.zeekling.cn/articles/2019/07/20/1563605756560.html) 
 > <p>和支持向量机一样， 决策树是一种多功能机器学习算法， 即可以执行分类任务也可以执行回归任务， 甚至包括多输出（multioutput）任务.</p>



---

本仓库通过 [github_zeekling](https://git.zeekling.cn/zeekling/github_zeekling) 自动进行同步更新 ❤️ 