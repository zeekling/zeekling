### Hey 👋, I'm [Zeek Ling](https://www/zeekling.cn)! 
![Github Stats](https://github-readme-stats.vercel.app/api?username=zeekling&show_icons=true) 
### 我在[小令童鞋](https://www.zeekling.cn)的近期动态

⭐️ Star [个人主页](https://github.com/zeekling/zeekling) 后会自动更新，最近更新时间：`2020-08-05 00:00:50`

<p align="center"><img alt="小令童鞋" src="https://img.zeekling.cn/images/2020/02/23/logo.th.png"></p><h2 align="center">小令童鞋
</h2>

<h4 align="center">梅干菜你个小酥饼哦。</h4>
<p align="center"><a title="小令童鞋" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/last-commit/zeekling/zeekling.svg?style=flat-square&color=FF9900"></a>
<a title="GitHub repo size in bytes" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/repo-size/zeekling/zeekling.svg?style=flat-square"></a>
<a title="Hits" target="_blank" href="https://github.com/zeekling/hits"><img src="https://hits.b3log.org/zeekling/zeekling.svg"></a></p>

### 最新

* 📝 [2020半年度总结](https://www.zeekling.cn/articles/2020/08/03/1596469503281.html) 
    > <p>转眼之间2020年已经过去一半时间了，时间过得真快，想想自己写<a href="https://www.zeekling.cn/articles/2019/08/27/1566917470370.html">2019年半年度总结</a>没过多久。总结下前半年的收获。</p>
* 📝 [2020年计划](https://www.zeekling.cn/articles/2020/01/01/1577875457805.html) 
    > <p>转眼之间已经到了 2020 年，按照往年的经验来讲是需要做一个 2020 年的计划。希望自己的 2020 年，是一个值得回忆，有所收获的一年，而不是碌碌无为的一年。</p>
* 📝 [自动跟新最新博客到github主页](https://www.zeekling.cn/articles/2020/07/26/1595773591724.html) 
    > <p>最近github可以显示类似于主页的东西了，所以打算将自己最新的博客推送到github主页。</p>
    > <p>我的github主页:<a href="https://github.com/zeekling" target="_blank">zeekling</a></p>
* 📝 [环材化生劝退计划](https://www.zeekling.cn/articles/2020/06/17/1592323471534.html) 
    > <p>环材化生劝退计划  劝退一人胜发七篇 CNS</p>
* 📝 [Redis 慢查询分析](https://www.zeekling.cn/articles/2020/07/23/1595493094855.html) 
    > <p>在慢查询的定义中，统计比较慢的时间段指的是<strong>命令执行</strong>这个步骤。没有慢查询，并不表示客户端没有超时问题，有可能网络传输有延迟，也有可能排队的命令比较多。</p>
    > <p>因为Redis中命令执行的排队机制，慢查询会导致其他命令的级联阻塞，所以当客户端出现请求超时的时候，需要检查该时间点是否有慢查询，从而分析出由于慢查询导致的命令级联阻塞。</p>
* 📝 [Redis Sentinel哨兵机制](https://www.zeekling.cn/articles/2020/07/21/1595343778998.html) 
    > <p>Redis的哨兵(sentinel) 系统用于管理多个 Redis 服务器,该系统执行以下三个任务:</p>
    > <p><strong>监控(Monitoring):</strong> 哨兵(sentinel) 会不断地检查你的Master和Slave是否运作正常。</p>
    > <p><strong>提醒(Notification):</strong> 当被监控的某个 Redis出现问题时, 哨兵(sentinel) 可以通过 API 向管理员或者其他应用程序发送通知。</p>
    > <p><strong>自动故障迁移(Automatic failover):</strong> 当一个Master不能正常工作时，哨兵(sentinel) 会开始一次自动故障迁移操作,它会将失效Master的其中一个Slave升级为新的Master, 并让失效Master的其他Slave改为复制新的Master; 当客户端试图连接失效的Master时,集群也会向客户端返回新Master的地址,使得集群可以使用Master代替失效Master。</p>
* 📝 [Redis 集群详解](https://www.zeekling.cn/articles/2020/07/21/1595342026052.html) 
    > <p>Redis Cluster 即 Redis 集群，是 Redis 官方在 3.0 版本推出的一套分布式存储方案。完全去中心化，由多个节点组成，所有节点彼此互联。Redis 客户端可以直接连接任何一节点获取集群中的键值对，不需要中间代理，如果该节点不存在用户所指定的键值，其内部会自动把客户端重定向到键值所在的节点。</p>
    > <p>Redis 集群是一个网状结构，每个节点都通过 TCP 连接跟其他每个节点连接。在一个有 N 个节点的集群中，每个节点都有 N-1 个流出的 TCP 连接，和 N-1 个流入的连接，这些 TCP 连接会永久保持。</p>
* 📝 [理解Redis的内存](https://www.zeekling.cn/articles/2020/07/04/1593860561539.html) 
    > <p>Redis 是一种内存数据库，将数据保存在内存中，读写效率要比传统的将数据保存在磁盘上的数据库要快很多。所以，监控 Redis 的内存消耗并了解 Redis 内存模型对高效并长期稳定使用 Redis 至关重要。</p>
* 📝 [机器学习知识点总结(长期更新)](https://www.zeekling.cn/articles/2019/08/14/1565788128215.html) 
    > <p>主要是为了列个机器学习相关的提纲,方便对已经学过的知识进行整理,相同的知识点,每次或者每个阶段都会有不同的想法,而我需要做的就是把自己的想法写下来.</p>
* 📝 [About Me](https://www.zeekling.cn/aboutMe.html) 
    > <p>本站主要是讲述一个自闭的二逼青年如何自救的一个过程，是一个消费大把大把青春的地方。</p>




